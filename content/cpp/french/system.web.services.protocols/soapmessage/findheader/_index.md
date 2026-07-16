---
title: FindHeader()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trouve la correspondance d'en-tête par le type d'en-tête spécifié.
type: docs
weight: 352
url: /fr/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) méthode

Trouve la correspondance d'en-tête par le type d'en-tête spécifié.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | La collection des correspondances d'en-tête. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | Le type d'en-tête à rechercher. |

### Valeur de retour

La correspondance d'en-tête.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)