---
title: XmlSeverityType
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente la gravité de l'événement de validation.
type: docs
weight: 1080
url: /fr/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Représente la gravité de l'événement de validation.

```cpp
enum class XmlSeverityType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Error | 0 | Indique qu'une erreur de validation s'est produite lors de la validation du document d'instance. Cela s'applique aux définitions de type de document (DTDs) et aux schémas XML [Schema](../) definition language (XSD). Les contraintes de validité du World Wide [Web](../../system.web/) Consortium (W3C) sont considérées comme des erreurs. Si aucun gestionnaire d'événement de validation n'a été créé, les erreurs lèvent une exception. |
| Warning | 1 | Indique qu'un événement de validation s'est produit et n'est pas une erreur. Un avertissement est généralement émis lorsqu'il n'y a pas de DTD, ou de XML [Schema](../) pour valider un élément ou un attribut particulier. Contrairement aux erreurs, les avertissements ne lèvent pas d'exception s'il n'y a pas de gestionnaire d'événement de validation. |

## Voir aussi

* Espace de noms [System::Xml::Schema](../)
* Bibliothèque [Aspose.Slides](../../)