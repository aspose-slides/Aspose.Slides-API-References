---
title: MoveToFollowing()
second_title: Справочник API Aspose.Slides для C++
description: Перемещает XPathNavigator к элементу с указанным локальным именем и URI пространства имён в порядке документа.
type: docs
weight: 703
url: /ru/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) метод

Перемещает [XPathNavigator](../) к элементу с указанным локальным именем и URI пространства имён в порядке документа.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя элемента. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён элемента. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещён; иначе **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) метод

Перемещает [XPathNavigator](../) к элементу с указанным локальным именем и URI пространства имён, к указанной границе, в порядке документа.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя элемента. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён элемента. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Объект [XPathNavigator](../), расположенный на границе элемента, за который текущий [XPathNavigator](../) не будет перемещаться при поиске следующего элемента. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещён; иначе **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) метод

Перемещает [XPathNavigator](../) к следующему элементу указанного XPathNodeType в порядке документа.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType элемента. XPathNodeType не может быть [XPathNodeType::Attribute](../../xpathnodetype/) или [XPathNodeType::Namespace](../../xpathnodetype/). |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещён; иначе **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) метод

Перемещает [XPathNavigator](../) к следующему элементу указанного XPathNodeType, к указанной границе, в порядке документа.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType элемента. XPathNodeType не может быть [XPathNodeType::Attribute](../../xpathnodetype/) или [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Объект [XPathNavigator](../), расположенный на границе элемента, за который текущий [XPathNavigator](../) не будет перемещаться при поиске следующего элемента. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещён; иначе **false**.

## См. также

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)