---
title: PreserveWhitespace()
second_title: Aspose.Slides C++ API Referencia
description: Ha egy származtatott osztályban felül van definiálva, kiértékeli, hogy meg kell-e őrizni a szóköz csomópontokat, vagy el kell-e távolítani őket az adott kontextusban.
type: docs
weight: 40
url: /hu/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) metódus


When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | A szóköz csomópont, amelyet a jelenlegi kontextusban meg kell őrizni vagy el kell távolítani. |

### Visszatérési érték

**true** ha a szóközt meg kell őrizni; **false** ha a szóközt el kell távolítani.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Osztály [XsltContext](../)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)