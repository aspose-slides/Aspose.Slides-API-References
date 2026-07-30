---
title: PreserveWhitespace()
second_title: Aspose.Slides pro C++ API Reference
description: Když je přepsána v odvozené třídě, vyhodnocuje, zda zachovat uzly bílých znaků nebo je odstranit v daném kontextu.
type: docs
weight: 40
url: /cs/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) metoda

Když je přepsána v odvozené třídě, vyhodnocuje, zda má v daném kontextu zachovat uzly bílých znaků nebo je odstranit.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Uzel bílých znaků, který má být v aktuálním kontextu zachován nebo odstraněn. |

### Návratová hodnota

**true** pokud má být bílý prostor zachován; **false** pokud má být bílý prostor odstraněn.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Třída [XsltContext](../)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)