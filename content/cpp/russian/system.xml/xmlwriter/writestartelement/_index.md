---
title: WriteStartElement()
second_title: Aspose.Slides для C++ справка API
description: При переопределении в производном классе записывает указанный начальный тег и связывает его с заданным пространством имён.
type: docs
weight: 92
url: /ru/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) метод

При переопределении в производном классе записывает указанный начальный тег и связывает его с указанным пространством имён.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя элемента. |
| ns | const [String](../../../system/string/)\& | URI пространства имён, которое необходимо связать с элементом. Если это пространство имён уже находится в области видимости и имеет связанный префикс, писатель автоматически также записывает этот префикс. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) метод

При переопределении в производном классе записывает указанный начальный тег и связывает его с указанным пространством имён и префиксом.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс пространства имён элемента. |
| localName | const [String](../../../system/string/)\& | Локальное имя элемента. |
| ns | const [String](../../../system/string/)\& | URI пространства имён, которое необходимо связать с элементом. |

## XmlWriter::WriteStartElement(const String\&) метод

При переопределении в производном классе записывает начальный тег с указанным локальным именем.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя элемента. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)