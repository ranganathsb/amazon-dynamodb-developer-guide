# Ruby and DynamoDB<a name="GettingStarted.Ruby"></a>

In this tutorial, you use the AWS SDK for Ruby to write simple programs to perform the following Amazon DynamoDB operations:

+ Create a table called `Movies` and load sample data in JSON format\.

+ Perform create, read, update, and delete operations on the table\.

+ Run simple queries\.

You use the downloadable version of DynamoDB in this tutorial\. For information about how to run the same code against the DynamoDB service, see the [Summary](GettingStarted.Ruby.Summary.md)\.

As you work through this tutorial, you can refer to the [AWS SDK for Ruby API Reference](http://docs.aws.amazon.com/sdkforruby/api/index.html)\. The [DynamoDB section](http://docs.aws.amazon.com/sdkforruby/api/Aws/DynamoDB.html) describes the parameters and results for DynamoDB operations\.

## Prerequisites<a name="GettingStarted.Ruby.Prereqs"></a>

+ Download and run DynamoDB on your computer\. For more information, see [Setting Up DynamoDB Local \(Downloadable Version\)](DynamoDBLocal.md)\. 

+ Set up an AWS access key to use the AWS SDKs\. For more information, see [Setting Up DynamoDB \(Web Service\)](SettingUp.DynamoWebService.md)\.

+ Set up the AWS SDK for Ruby:

  + Go to [https://www\.ruby\-lang\.org/en/documentation/installation/](https://www.ruby-lang.org/en/documentation/installation/) and install Ruby\.

  + Go to [https://aws\.amazon\.com/sdk\-for\-ruby](https://aws.amazon.com/sdk-for-ruby/) and install the AWS SDK for Ruby\.

  For more information, see [Installation](http://docs.aws.amazon.com/sdkforruby/api/index.html#Installation) in the *AWS SDK for Ruby API Reference*\.