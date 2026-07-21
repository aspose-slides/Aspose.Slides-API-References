---
title: SelectDescendants()
second_title: Aspose.Slides для C++ справочник API
description: Выбирает все дочерние узлы текущего узла, которые имеют соответствующий XPathNodeType.
type: docs
weight: 859
url: /ru/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) метод

Выбирает все дочерние узлы текущего узла, которые имеют соответствующий XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType дочерних узлов. |
| matchSelf | **bool** | **true** чтобы включить контекстный узел в выборку; иначе **false**. |

### Возвращаемое значение

Экземпляр [XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы.

## XPathNavigator::SelectDescendants(String, String, bool) метод

Выбирает все дочерние узлы текущего узла с указанным локальным именем и URI пространства имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя дочерних узлов. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён дочерних узлов. |
| matchSelf | **bool** | **true** чтобы включить контекстный узел в выборку; иначе **false**. |

### Возвращаемое значение

Экземпляр [XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы.

## См. также

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)