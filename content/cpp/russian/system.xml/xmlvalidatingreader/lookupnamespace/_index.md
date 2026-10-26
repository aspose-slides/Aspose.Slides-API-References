---
title: LookupNamespace()
second_title: Aspose.Slides для C++: справка API
description: Разрешает префикс пространства имён в области действия текущего элемента.
type: docs
weight: 547
url: /ru/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) метод


Разрешает префикс пространства имён в области действия текущего элемента.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс, чей Uniform Resource Identifier (URI) пространства имён вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте пустую строку. |

### Возвращаемое значение

URI пространства имён, к которому соответствует префикс, или **nullptr**, если подходящий префикс не найден.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)