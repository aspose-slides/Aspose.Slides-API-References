---
title: get_ValidationFlags()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce un valore che indica le impostazioni di convalida dello schema. Questa impostazione si applica agli oggetti XmlReader che convalidano gli schemi (XmlReaderSettings::get_ValidationType valore è ValidationType::Schema)."
type: docs
weight: 378
url: /it/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() metodo


Restituisce un valore che indica le impostazioni di convalida dello schema. Questa impostazione si applica agli oggetti [XmlReader](../../xmlreader/) che convalidano gli schemi (il valore [XmlReaderSettings::get_ValidationType](../get_validationtype/) è [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Valore di ritorno

Una combinazione bitwise di valori di enumerazione che specificano le opzioni di convalida. XmlSchemaValidationFlags::ProcessIdentityConstraints e XmlSchemaValidationFlags::AllowXmlAttributes sono abilitati per impostazione predefinita. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation e XmlSchemaValidationFlags::ReportValidationWarnings sono disabilitati per impostazione predefinita.

## Vedi anche

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Classe [XmlReaderSettings](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)