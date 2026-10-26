---
title: PreserveWhitespace()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Gdy zostanie nadpisana w klasie pochodnej, ocenia, czy w danym kontekście zachować węzły białych znaków, czy je usunąć.
type: docs
weight: 40
url: /pl/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) metoda

Gdy zostanie nadpisana w klasie pochodnej, ocenia, czy w danym kontekście zachować węzły białych znaków, czy je usunąć.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Węzeł białych znaków, który ma być zachowany lub usunięty w bieżącym kontekście. |

### Wartość zwracana

**true**, jeśli białe znaki mają być zachowane; **false**, jeśli białe znaki mają być usunięte.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasa [XsltContext](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)