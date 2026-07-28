---
title: get_ValidationFlags()
second_title: Aspose.Slides for C++ API hivatkozás
description: "Egy olyan értéket ad vissza, amely a séma ellenőrzési beállításokat jelzi. Ez a beállítás olyan XmlReader objektumokra vonatkozik, amelyek sémákat ellenőrznek (az XmlReaderSettings::get_ValidationType értéke ValidationType::Schema)."
type: docs
weight: 378
url: /hu/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() metódus


Egy olyan értéket ad vissza, amely a séma érvényesítési beállításokat jelzi. Ez a beállítás [XmlReader](../../xmlreader/) objektumokra vonatkozik, amelyek sémákat érvényesítenek ([XmlReaderSettings::get_ValidationType](../get_validationtype/) érték [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Visszatérési érték

Egy bitenkénti kombinációja az érvényesítési beállításokat meghatározó enumerációs értékeknek. Az XmlSchemaValidationFlags::ProcessIdentityConstraints és az XmlSchemaValidationFlags::AllowXmlAttributes alapértelmezés szerint engedélyezve van. Az XmlSchemaValidationFlags::ProcessInlineSchema, az XmlSchemaValidationFlags::ProcessSchemaLocation és az XmlSchemaValidationFlags::ReportValidationWarnings alapértelmezés szerint le vannak tiltva.

## Lásd még

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Osztály [XmlReaderSettings](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)