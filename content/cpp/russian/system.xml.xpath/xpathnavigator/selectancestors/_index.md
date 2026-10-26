---
title: SelectAncestors()
second_title: Справочник API Aspose.Slides для C++
description: Выбирает все узлы-предки текущего узла, имеющие соответствующий XPathNodeType.
type: docs
weight: 846
url: /ru/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) метод

Выбирает все узлы-предки текущего узла, имеющие соответствующий XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType предков узлов. |
| matchSelf | **bool** | Для включения контекстного узла в выборку, **true**; иначе, **false**. |

### Возвращаемое значение

[XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы. Возвращённые узлы находятся в обратном порядке документа.

## XPathNavigator::SelectAncestors(String, String, bool) метод

Выбирает все узлы-предки текущего узла, имеющие указанные локальное имя и URI пространства имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя предков узлов. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён предков узлов. |
| matchSelf | **bool** | Для включения контекстного узла в выборку, **true**; иначе, **false**. |

### Возвращаемое значение

[XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы. Возвращённые узлы находятся в обратном порядке документа.

## См. также

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)