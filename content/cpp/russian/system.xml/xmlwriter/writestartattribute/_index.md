---
title: WriteStartAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Записывает начало атрибута с указанным локальным именем и URI пространства имён.
type: docs
weight: 144
url: /ru/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) метод

Записывает начало атрибута с указанным локальным именем и URI пространства имён.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| ns | const [String](../../../system/string/)\& | URI пространства имён атрибута. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) метод

При переопределении в производном классе записывает начало атрибута с указанным префиксом, локальным именем и URI пространства имён.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс пространства имён атрибута. |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| ns | const [String](../../../system/string/)\& | URI пространства имён атрибута. |

## XmlWriter::WriteStartAttribute(const String\&) метод

Записывает начало атрибута с указанным локальным именем.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)