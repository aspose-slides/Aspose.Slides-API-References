---
title: SelectChildren()
second_title: Aspose.Slides для C++ — справка по API
description: Выбирает все дочерние узлы текущего узла, которые имеют соответствующий XPathNodeType.
type: docs
weight: 833
url: /ru/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) метод

Выбирает все дочерние узлы текущего узла, которые имеют соответствующий XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType дочерних узлов. |

### Возвращаемое значение

[XPathNodeIterator](../../xpathnodeiterator/) который содержит выбранные узлы.

## XPathNavigator::SelectChildren(String, String) метод

Выбирает все дочерние узлы текущего узла, у которых указаны локальное имя и URI пространства имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя дочерних узлов. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён дочерних узлов. |

### Возвращаемое значение

[XPathNodeIterator](../../xpathnodeiterator/) который содержит выбранные узлы.

## См. также

* Перечисление [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XPathNodeIterator](../../xpathnodeiterator/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)