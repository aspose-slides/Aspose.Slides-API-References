---
title: ReadElementContentAsObject()
second_title: Справочник API Aspose.Slides для C++
description: Считывает текущий элемент и возвращает содержимое в виде объекта.
type: docs
weight: 469
url: /ru/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() метод

Считывает текущий элемент и возвращает содержимое в виде [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Возвращаемое значение

Упакованный объект наиболее подходящего типа. Значение [XmlReader::get_ValueType](../get_valuetype/) определяет подходящий тип. Если содержимое имеет тип списка, этот метод возвращает массив упакованных объектов соответствующего типа.

## XmlReader::ReadElementContentAsObject(String, String) метод

Проверяет, что указанные локальное имя и URI пространства имен соответствуют текущему элементу, затем считывает текущий элемент и возвращает содержимое в виде [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя элемента. |
| namespaceURI | [String](../../../system/string/) | URI пространства имен элемента. |

### Возвращаемое значение

Упакованный объект наиболее подходящего типа. Значение [XmlReader::get_ValueType](../get_valuetype/) определяет соответствующий тип. Если содержимое имеет тип списка, этот метод возвращает массив упакованных объектов соответствующего типа.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [XmlReader](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)