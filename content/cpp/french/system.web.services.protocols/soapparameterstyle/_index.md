---
title: SoapParameterStyle
second_title: Référence de l'API Aspose.Slides pour C++
description: Énumère les formats des paramètres dans un message SOAP.
type: docs
weight: 183
url: /fr/system.web.services.protocols/soapparameterstyle/
---
## SoapParameterStyle enum

Énumère les formats des paramètres dans un message SOAP.

```cpp
enum class SoapParameterStyle
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Si '[SoapDocumentServiceAttribute](../soapdocumentserviceattribute/)' n'est pas appliqué à la classe, alors la valeur par défaut est 'Wrapped'. |
| Bare | 1 | Les paramètres sont placés dans des éléments XML qui suivent l'élément 'Body'. |
| Wrapped | 2 | Les paramètres sont encapsulés dans un seul élément XML qui suit l'élément 'Body'. |

## Voir aussi

* Espace de noms [System::Web::Services::Protocols](../)
* Bibliothèque [Aspose.Slides](../../)