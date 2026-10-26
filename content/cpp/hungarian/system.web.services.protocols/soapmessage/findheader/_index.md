---
title: FindHeader()
second_title: Aspose.Slides C++ API referenciája
description: Megkeresi a fejléc leképezést a megadott fejléc típus alapján.
type: docs
weight: 352
url: /hu/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) metódus

Kikeresi a fejléc leképezést a megadott fejléc típus alapján.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | A fejléc leképezések gyűjteménye. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | A keresett fejléc típus. |

### Visszatérési érték

A fejléc leképezés.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)