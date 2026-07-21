---
title: get_ValidationFlags()
second_title: Aspose.Slides для C++ — справка API
description: "Возвращает значение, указывающее параметры проверки схемы. Этот параметр применяется к объектам XmlReader, которые проверяют схемы (значение XmlReaderSettings::get_ValidationType равно ValidationType::Schema)."
type: docs
weight: 378
url: /ru/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() метод

Возвращает значение, указывающее параметры проверки схемы. Этот параметр применяется к объектам [XmlReader](../../xmlreader/), которые проверяют схемы (значение [XmlReaderSettings::get_ValidationType](../get_validationtype/) равно [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Возвращаемое значение

Комбинация значений перечисления, задающих параметры проверки, с использованием побитовых операций. По умолчанию включены XmlSchemaValidationFlags::ProcessIdentityConstraints и XmlSchemaValidationFlags::AllowXmlAttributes. По умолчанию отключены XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation и XmlSchemaValidationFlags::ReportValidationWarnings.

## См. также

* Перечисление [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Класс [XmlReaderSettings](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)