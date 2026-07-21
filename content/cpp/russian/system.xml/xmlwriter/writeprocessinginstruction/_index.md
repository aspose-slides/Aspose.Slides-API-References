---
title: WriteProcessingInstruction()
second_title: Aspose.Slides для C++ справочник API
description: "При переопределении в производном классе записывает инструкцию обработки с пробелом между именем и текстом следующим образом: <?name text?>."
type: docs
weight: 196
url: /ru/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) метод

При переопределении в производном классе записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя инструкции обработки. |
| text | [String](../../../system/string/) | Текст, включаемый в инструкцию обработки. |
## Примечания

Этот метод используется для создания объявления XML после того, как [XmlWriter::WriteStartDocument](../writestartdocument/) уже был вызван. 
## См. также

* Класс [String](../../../system/string/)
* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)