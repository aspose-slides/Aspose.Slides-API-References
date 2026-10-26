---
title: WriteProcessingInstruction()
second_title: Aspose.Slides для C++: справочник API
description: "Записывает инструкцию обработки с пробелом между именем и текстом следующим образом: <?name text?>."
type: docs
weight: 326
url: /ru/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) метод

Записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя инструкции обработки. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) для включения в инструкцию обработки. |
## Примечания

Этот метод используется для создания декларации XML после того, как [XmlTextWriter::WriteStartDocument](../writestartdocument/) уже был вызван. 
## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextWriter](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)