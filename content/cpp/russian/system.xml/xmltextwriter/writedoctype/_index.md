---
title: WriteDocType()
second_title: Aspose.Slides для C++: справочник API
description: Записывает объявление DOCTYPE с указанным именем и необязательными атрибутами.
type: docs
weight: 222
url: /ru/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) method

Записывает объявление DOCTYPE с указанным именем и необязательными атрибутами.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя DOCTYPE. Должно быть непустым. |
| pubid | const [String](../../../system/string/)\& | Если не null, также записывает PUBLIC \"pubid\" \"sysid\", где **pubid** и **sysid** заменяются значением переданных аргументов. |
| sysid | const [String](../../../system/string/)\& | Если **pubid** равно null и **sysid** не null, записывает SYSTEM \"sysid\", где **sysid** заменяется значением данного аргумента. |
| subset | const [String](../../../system/string/)\& | Если не null, записывает [subset], где subset заменяется значением данного аргумента. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)