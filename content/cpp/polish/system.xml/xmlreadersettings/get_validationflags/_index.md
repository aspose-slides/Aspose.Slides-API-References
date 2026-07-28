---
title: get_ValidationFlags()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Zwraca wartość wskazującą ustawienia walidacji schematu. To ustawienie obowiązuje obiekty XmlReader, które walidują schematy (XmlReaderSettings::get_ValidationType wartość to ValidationType::Schema)."
type: docs
weight: 378
url: /pl/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() metoda

Zwraca wartość wskazującą ustawienia walidacji schematu. To ustawienie obowiązuje obiekty [XmlReader](../../xmlreader/) walidujące schematy ([XmlReaderSettings::get_ValidationType](../get_validationtype/) wartość to [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Wartość zwracana

Kombinacja bitowa wartości wyliczeniowych określających opcje walidacji. XmlSchemaValidationFlags::ProcessIdentityConstraints i XmlSchemaValidationFlags::AllowXmlAttributes są domyślnie włączone. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation i XmlSchemaValidationFlags::ReportValidationWarnings są domyślnie wyłączone.

## Zobacz także

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Klasa [XmlReaderSettings](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)