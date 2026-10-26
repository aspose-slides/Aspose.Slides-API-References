---
title: FindHeader()
second_title: Aspose.Slides för C++ API-referens
description: Hitta header-mappningen för angiven headertyp.
type: docs
weight: 352
url: /sv/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) method

Hitta header-mappningen för angiven headdertyp.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Samlingen av header-mappningarna. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | Header-typen att söka efter. |

### Return Value

Header-mappningen.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)