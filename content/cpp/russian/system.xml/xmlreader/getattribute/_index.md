---
title: GetAttribute()
second_title: Aspose.Slides для C++ – справка API
description: "При переопределении в производном классе получает значение атрибута с указанным значением XmlReader::get_Name."
type: docs
weight: 599
url: /ru/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) метод

When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное (квалифицированное) имя атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден или значение равно [String::Empty](../../../system/string/empty/), **nullptr** возвращается.

## XmlReader::GetAttribute(String, String) метод

When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден или значение равно [String::Empty](../../../system/string/empty/), **nullptr** возвращается. Этот метод не перемещает считыватель.

## XmlReader::GetAttribute(int32_t) метод

When overridden in a derived class, gets the value of the attribute with the specified index.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### Возвращаемое значение

Значение указанного атрибута. Этот метод не перемещает считыватель.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)