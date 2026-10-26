---
title: FindHeader()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet die Header-Zuordnung anhand des angegebenen Header-Typs.
type: docs
weight: 352
url: /de/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) Methode

Findet die Header-Zuordnung anhand des angegebenen Header-Typs.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Die Sammlung der Header-Zuordnungen. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | Der Header-Typ, nach dem gesucht wird. |

### Rückgabewert

Die Header-Zuordnung.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [SoapMessage](../)
* Namensraum [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)