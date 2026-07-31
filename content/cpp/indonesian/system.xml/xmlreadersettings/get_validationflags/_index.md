---
title: get_ValidationFlags()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan nilai yang menunjukkan pengaturan validasi skema. Pengaturan ini berlaku untuk objek XmlReader yang memvalidasi skema (nilai XmlReaderSettings::get_ValidationType adalah ValidationType::Schema)."
type: docs
weight: 378
url: /id/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() method


Mengembalikan nilai yang menunjukkan pengaturan validasi skema. Pengaturan ini berlaku untuk [XmlReader](../../xmlreader/) objek yang memvalidasi skema (nilai [XmlReaderSettings::get_ValidationType](../get_validationtype/) adalah [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Nilai Kembalian

Kombinasi bitwise dari nilai enumerasi yang menentukan opsi validasi. XmlSchemaValidationFlags::ProcessIdentityConstraints dan XmlSchemaValidationFlags::AllowXmlAttributes diaktifkan secara default. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation, dan XmlSchemaValidationFlags::ReportValidationWarnings dinonaktifkan secara default.

## Lihat Juga

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)