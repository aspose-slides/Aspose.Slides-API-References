---
title: FindHeader()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoek de header mapping op basis van het opgegeven header type.
type: docs
weight: 352
url: /nl/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) methode

Zoek de headermapping op basis van het opgegeven headertype.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | De verzameling van de header mappings. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | Het headertype om naar te zoeken. |

### Retourwaarde

De headermapping.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [SoapMessage](../)
* Naamruimte [System::Web::Services::Protocols](../../)
* Bibliotheek [Aspose.Slides](../../../)