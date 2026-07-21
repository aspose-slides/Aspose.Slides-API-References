---
title: SelectSingleNode()
second_title: Aspose.Slides для C++ справочник API
description: Выбирает первый XmlNode, который соответствует выражению XPath.
type: docs
weight: 352
url: /ru/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) метод


Выбирает первый [XmlNode](../), который соответствует выражению [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Выражение [XPath](../../../system.xml.xpath/). |

### Возвращаемое значение

Первый [XmlNode](../), который соответствует запросу [XPath](../../../system.xml.xpath/), или **nullptr**, если подходящий узел не найден.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) метод


Выбирает первый [XmlNode](../), который соответствует выражению [XPath](../../../system.xml.xpath/). Любые префиксы, найденные в выражении [XPath](../../../system.xml.xpath/), разрешаются с помощью предоставленного [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Выражение [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Объект [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для разрешения пространств имён для префиксов в выражении [XPath](../../../system.xml.xpath/). |

### Возвращаемое значение

Первый [XmlNode](../), который соответствует запросу [XPath](../../../system.xml.xpath/), или **nullptr**, если подходящий узел не найден.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../)
* Класс [String](../../../system/string/)
* Класс [XmlNamespaceManager](../../xmlnamespacemanager/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)