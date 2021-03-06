# Spinen\ConnectWise\Clients\Mobile\SendEmailConflictsApi
Spinen&#39;s PHP ConnectWise Client for Mobile API generated by Swagger Code Generator.

All URIs are relative to *https://api-na.myconnectwise.net/v4_6_release/apis/3.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**mobileEmailsConflictPost**](SendEmailConflictsApi.md#mobileEmailsConflictPost) | **POST** /mobile/emails/conflict | 


# **mobileEmailsConflictPost**
> mobileEmailsConflictPost($request)



Check Email Conflicts

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure HTTP basic authorization: BasicAuth
Spinen\ConnectWise\Clients\Mobile\Configuration::getDefaultConfiguration()->setUsername('YOUR_USERNAME');
Spinen\ConnectWise\Clients\Mobile\Configuration::getDefaultConfiguration()->setPassword('YOUR_PASSWORD');

$api_instance = new Spinen\ConnectWise\Clients\Mobile\Api\SendEmailConflictsApi();
$request = new \Spinen\ConnectWise\Clients\Mobile\Model\EmailConflictRequest(); // \Spinen\ConnectWise\Clients\Mobile\Model\EmailConflictRequest | 

try {
    $api_instance->mobileEmailsConflictPost($request);
} catch (Exception $e) {
    echo 'Exception when calling SendEmailConflictsApi->mobileEmailsConflictPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**\Spinen\ConnectWise\Clients\Mobile\Model\EmailConflictRequest**](../Model/\Spinen\ConnectWise\Clients\Mobile\Model\EmailConflictRequest.md)|  |

### Return type

void (empty response body)

### Authorization

[BasicAuth](../../README.md#BasicAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

