---
title: get_Current()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Když je v odvozené třídě přepsáno, získá objekt XPathNavigator pro tento XPathNodeIterator, umístěný na aktuálním kontextovém uzlu.
type: docs
weight: 1
url: /cs/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metoda

Když je v odvozené třídě přepsáno, získá objekt [XPathNavigator](../../xpathnavigator/) pro tento [XPathNodeIterator](../), umístěný na aktuálním kontextovém uzlu.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Návratová hodnota

Objekt [XPathNavigator](../../xpathnavigator/) umístěný na kontextovém uzlu, ze kterého byl vybrán uzlový soubor. Metoda [XPathNodeIterator::MoveNext](../movenext/) musí být zavolána k přesunutí [XPathNodeIterator](../) na první uzel ve vybraném souboru.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../xpathnavigator/)
* Class [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)