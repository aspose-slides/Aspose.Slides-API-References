---
title: LookupNamespace()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе разрешает префикс пространства имён в области действия текущего элемента.
type: docs
weight: 729
url: /ru/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) метод

При переопределении в производном классе разрешает префикс пространства имён в области действия текущего элемента.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс, пространство имён URI которого вы хотите разрешить. Чтобы сопоставить пространство имён по умолчанию, передайте пустую строку. |

### Возвращаемое значение

URI пространства имён, к которому сопоставлен префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)