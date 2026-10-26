---
title: WriteStartDocument()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе записывает объявление XML с версией \"1.0\".
type: docs
weight: 53
url: /ru/system.xml/xmlwriter/writestartdocument/
---
## XmlWriter::WriteStartDocument() метод

При переопределении в производном классе записывает объявление XML с версией "1.0".

```cpp
virtual void System::Xml::XmlWriter::WriteStartDocument()=0
```

## XmlWriter::WriteStartDocument(bool) метод

При переопределении в производном классе записывает объявление XML с версией "1.0" и атрибутом standalone.

```cpp
virtual void System::Xml::XmlWriter::WriteStartDocument(bool standalone)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| standalone | **bool** | Если **true**, он пишет "standalone=yes"; если **false**, он пишет "standalone=no". |

## См. также

* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)