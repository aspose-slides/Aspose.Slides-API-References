---
title: ReadStartElement()
second_title: Справка API Aspose.Slides для C++
description: Проверяет, что текущий узел является элементом, и перемещает читатель к следующему узлу.
type: docs
weight: 846
url: /ru/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() метод

Проверяет, что текущий узел является элементом, и перемещает читатель к следующему узлу.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) метод

Проверяет, что текущий узел содержимого является элементом с заданным значением [XmlReader::get_Name](../get_name/) и перемещает читатель к следующему узлу.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя элемента. |

## XmlReader::ReadStartElement(String, String) метод

Проверяет, что текущий узел содержимого является элементом с заданными значениями [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) и перемещает читатель к следующему узлу.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Локальное имя элемента. |
| ns | [String](../../../system/string/) | URI пространства имён элемента. |

## См. также

* Класс [XmlReader](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)