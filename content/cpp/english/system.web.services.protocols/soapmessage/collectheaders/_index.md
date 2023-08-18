---
title: CollectHeaders()
second_title: Aspose.Slides for C++ API Reference
description: Sets the internal collection of the SOAP headers.
type: docs
weight: 326
url: /system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) method


Sets the internal collection of the SOAP headers.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to get the SOAP headers from. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | A collection of headers from which the internal collection will be filled. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | The SOAP header direction. |

## See Also

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)