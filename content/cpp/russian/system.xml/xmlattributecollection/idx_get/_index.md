---
title: idx_get()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает атрибут с указанным индексом.
type: docs
weight: 1
url: /ru/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) метод

Возвращает атрибут с указанным индексом.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. |

### Возвращаемое значение

Атрибут с указанным индексом.

## XmlAttributeCollection::idx_get(const String\&) метод

Возвращает атрибут с указанным именем.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Полное имя атрибута. |

### Возвращаемое значение

Атрибут с указанным именем. Если атрибут не существует, этот метод возвращает **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) метод

Возвращает атрибут с указанным локальным именем и Uniform Resource Identifier (URI) пространства имён.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имён атрибута. |

### Возвращаемое значение

Атрибут с указанным локальным именем и URI пространства имён. Если атрибут не существует, этот метод возвращает **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlAttribute](../../xmlattribute/)
* Класс [XmlAttributeCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)