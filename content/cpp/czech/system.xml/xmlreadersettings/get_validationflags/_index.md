---
title: get_ValidationFlags()
second_title: Aspose.Slides pro C++ - reference API
description: "Vrací hodnotu, která označuje nastavení validace schématu. Toto nastavení platí pro objekty XmlReader, které validují schémata (hodnota XmlReaderSettings::get_ValidationType je ValidationType::Schema)."
type: docs
weight: 378
url: /cs/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() method


Vrací hodnotu, která označuje nastavení validace schématu. Toto nastavení platí pro objekty [XmlReader](../../xmlreader/), které validují schémata (hodnota [XmlReaderSettings::get_ValidationType](../get_validationtype/) je [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Návratová hodnota

Bitová kombinace hodnot výčtu, které specifikují možnosti validace. XmlSchemaValidationFlags::ProcessIdentityConstraints a XmlSchemaValidationFlags::AllowXmlAttributes jsou ve výchozím nastavení povoleny. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation a XmlSchemaValidationFlags::ReportValidationWarnings jsou ve výchozím nastavení zakázány.

## Viz také

* Výčet [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Třída [XmlReaderSettings](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)