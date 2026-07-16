---
title: XmlSchemaValidationFlags
second_title: Référence API Aspose.Slides pour C++
description: Spécifie les options de validation du schéma utilisées par les classes XmlSchemaValidator et XmlReader.
type: docs
weight: 1054
url: /fr/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum


Spécifie les options de validation du schéma utilisées par les classes [XmlSchemaValidator](../xmlschemavalidator/) et [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Values

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Ne pas traiter les contraintes d’identité, les schémas intégrés, les indications d’emplacement du schéma, ou signaler les avertissements de validation du schéma. |
| ProcessInlineSchema | 1 | Traiter les schémas intégrés rencontrés pendant la validation. |
| ProcessSchemaLocation | 2 | Traiter les indications d’emplacement du schéma (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) rencontrées pendant la validation. |
| ReportValidationWarnings | 4 | Signaler les avertissements de validation du schéma rencontrés pendant la validation. |
| ProcessIdentityConstraints | 8 | Traiter les contraintes d’identité (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) rencontrées pendant la validation. |
| AllowXmlAttributes | 16 | Autoriser les attributs xml:* même s’ils ne sont pas définis dans le schéma. Les attributs seront validés en fonction de leur type de données. |

## See Also

* Espace de noms [System::Xml::Schema](../)
* Bibliothèque [Aspose.Slides](../../)