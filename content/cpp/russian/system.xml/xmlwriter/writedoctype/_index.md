---
title: WriteDocType()
second_title: Aspose.Slides для C++ справочника API
description: При переопределении в производном классе записывает объявление DOCTYPE с указанным именем и необязательными атрибутами.
type: docs
weight: 79
url: /ru/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) метод


При переопределении в производном классе записывает объявление DOCTYPE с указанным именем и необязательными атрибутами.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя DOCTYPE. Оно должно быть не пустым. |
| pubid | const [String](../../../system/string/)\& | Если не null, также записывает PUBLIC \"pubid\" \"sysid\", где **pubid** и **sysid** заменяются значениями переданных аргументов. |
| sysid | const [String](../../../system/string/)\& | Если **pubid** равен **nullptr** и **sysid** не null, записывает SYSTEM \"sysid\", где **sysid** заменяется значением этого аргумента. |
| subset | const [String](../../../system/string/)\& | Если не null, записывает [subset], где subset заменяется значением этого аргумента. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)