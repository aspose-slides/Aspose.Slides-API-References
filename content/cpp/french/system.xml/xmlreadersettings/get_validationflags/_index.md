---
title: get_ValidationFlags()
second_title: Référence API Aspose.Slides pour C++
description: "Renvoie une valeur indiquant les paramètres de validation du schéma. Ce paramètre s'applique aux objets XmlReader qui valident les schémas (XmlReaderSettings::get_ValidationType valeur est ValidationType::Schema)."
type: docs
weight: 378
url: /fr/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() méthode

Renvoie une valeur indiquant les paramètres de validation du schéma. Ce paramètre s'applique aux objets [XmlReader](../../xmlreader/) qui valident les schémas (la valeur [XmlReaderSettings::get_ValidationType](../get_validationtype/) est [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Valeur de retour

Une combinaison binaire de valeurs d'énumération qui spécifient les options de validation. XmlSchemaValidationFlags::ProcessIdentityConstraints et XmlSchemaValidationFlags::AllowXmlAttributes sont activés par défaut. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation et XmlSchemaValidationFlags::ReportValidationWarnings sont désactivés par défaut.

## Voir aussi

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* classe [XmlReaderSettings](../)
* espace de noms [System::Xml](../../)
* bibliothèque [Aspose.Slides](../../../)