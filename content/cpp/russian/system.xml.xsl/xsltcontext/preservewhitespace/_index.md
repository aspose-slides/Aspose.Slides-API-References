---
title: PreserveWhitespace()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе определяет, следует ли сохранять узлы пробельных символов или удалять их в данном контексте.
type: docs
weight: 40
url: /ru/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) метод

При переопределении в производном классе определяет, следует ли сохранять узлы пробельных символов или удалять их для данного контекста.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Узел пробельных символов, который должен быть сохранён или удалён в текущем контексте. |

### Возвращаемое значение

**true** если пробельные символы должны быть сохранены; **false** если пробельные символы должны быть удалены.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Класс [XsltContext](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)