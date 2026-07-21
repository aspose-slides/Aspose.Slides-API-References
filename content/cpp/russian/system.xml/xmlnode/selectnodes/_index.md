---
title: SelectNodes()
second_title: Aspose.Slides для C++ API Reference
description: Выбирает список узлов, соответствующих выражению XPath.
type: docs
weight: 365
url: /ru/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) метод


Выбирает список узлов, соответствующих выражению [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Выражение [XPath](../../../system.xml.xpath/). |

### Return Value

[XmlNodeList](../../xmlnodelist/), содержащий коллекцию узлов, соответствующих запросу [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) метод


Выбирает список узлов, соответствующих выражению [XPath](../../../system.xml.xpath/). Любые префиксы, найденные в выражении [XPath](../../../system.xml.xpath/), разрешаются с помощью предоставленного [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Выражение [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для разрешения пространств имён для префиксов в выражении [XPath](../../../system.xml.xpath/). |

### Return Value

[XmlNodeList](../../xmlnodelist/), содержащий коллекцию узлов, соответствующих запросу [XPath](../../../system.xml.xpath/).

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNodeList](../../xmlnodelist/)
* Класс [String](../../../system/string/)
* Класс [XmlNode](../)
* Класс [XmlNamespaceManager](../../xmlnamespacemanager/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)