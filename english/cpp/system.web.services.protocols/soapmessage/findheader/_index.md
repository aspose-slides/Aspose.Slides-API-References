---
title: FindHeader()
second_title: Aspose.Slides for C++ API Reference
description: Find the header mapping by specified header type.
type: docs
weight: 352
url: /cpp/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader([System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../../system/typeinfo/)\&) method


Find the header mapping by specified header type.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | The collection of the header mappings. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | The header type to look for. |

### Return Value

The header mapping.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)
