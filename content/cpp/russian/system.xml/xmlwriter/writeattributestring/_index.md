---
title: WriteAttributeString()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе записывает атрибут с указанным локальным именем, URI пространства имён и значением.
type: docs
weight: 131
url: /ru/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) метод

При переопределении в производном классе записывает атрибут с указанным локальным именем, URI пространства имён и значением.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| ns | const [String](../../../system/string/)\& | URI пространства имён, связываемое с атрибутом. |
| value | const [String](../../../system/string/)\& | Значение атрибута. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) метод

При переопределении в производном классе записывает атрибут с указанным локальным именем и значением.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| value | const [String](../../../system/string/)\& | Значение атрибута. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) метод

При переопределении в производном классе записывает атрибут с указанным префиксом, локальным именем, URI пространства имён и значением.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс пространства имён атрибута. |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| ns | const [String](../../../system/string/)\& | URI пространства имён атрибута. |
| value | const [String](../../../system/string/)\& | Значение атрибута. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)