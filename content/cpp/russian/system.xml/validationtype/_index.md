---
title: ValidationType
second_title: Справочник API Aspose.Slides для C++
description: Указывает тип проверки, которую необходимо выполнить.
type: docs
weight: 729
url: /ru/system.xml/validationtype/
---
## ValidationType enum

Указывает тип проверки, которую необходимо выполнить.

```cpp
enum class ValidationType
```

### Значения

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Проверка не выполняется, и ошибки проверки не генерируются. Эта настройка создаёт парсер, совместимый с XML 1.0, без проверки. |
| Auto | 1 | Выполняет проверку, если найдена информация DTD или схемы. |
| DTD | 2 | Выполняет проверку согласно DTD. |
| XDR | 3 | Выполняет проверку согласно схемам XML-Data Reduced (XDR), включая встроенные схемы XDR. Схемы XDR распознаются с помощью префикса пространства имён **x-schema** или значения [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Выполняет проверку согласно схемам языка определения XML [Schema](../../system.xml.schema/) (XSD), включая встроенные XML-схемы. XML-схемы связываются с URI пространств имён либо с помощью атрибута **schemaLocation**, либо через предоставленные **Schemas**. |

## См. также

* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)