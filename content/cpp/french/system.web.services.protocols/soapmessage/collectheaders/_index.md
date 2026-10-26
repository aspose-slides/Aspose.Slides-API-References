---
title: CollectHeaders()
second_title: Référence API Aspose.Slides pour C++
description: Définit la collection interne des en-têtes SOAP.
type: docs
weight: 326
url: /fr/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) méthode

Définit la collection interne des en-têtes SOAP.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L’objet dont les en-têtes SOAP sont récupérées. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Une collection d’en-têtes à partir de laquelle la collection interne sera remplie. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | La direction de l’en-tête SOAP. |

## Voir aussi

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [SoapMessage](../)
* Espace de noms [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)