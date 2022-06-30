# Swagger\Client\SimpleCampaignSMSApi

All URIs are relative to *http://api.orange.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**simpleCampaignSMSCreate**](SimpleCampaignSMSApi.md#simpleCampaignSMSCreate) | **POST** /api/v1/sms/simple | create simpleCampaignSMS


# **simpleCampaignSMSCreate**
> \Swagger\Client\Model\SimpleCampaignSMS simpleCampaignSMSCreate($simple_campaign_sms)

create simpleCampaignSMS

Specific business errors for current operation will be encapsulated in  HTTP Response 422 Unprocessable entity

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\SimpleCampaignSMSApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$simple_campaign_sms = new \Swagger\Client\Model\SimpleCampaignSMS(); // \Swagger\Client\Model\SimpleCampaignSMS | 

try {
    $result = $apiInstance->simpleCampaignSMSCreate($simple_campaign_sms);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SimpleCampaignSMSApi->simpleCampaignSMSCreate: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **simple_campaign_sms** | [**\Swagger\Client\Model\SimpleCampaignSMS**](../Model/SimpleCampaignSMS.md)|  |

### Return type

[**\Swagger\Client\Model\SimpleCampaignSMS**](../Model/SimpleCampaignSMS.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json;charset=utf-8
 - **Accept**: application/json;charset=utf-8

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

