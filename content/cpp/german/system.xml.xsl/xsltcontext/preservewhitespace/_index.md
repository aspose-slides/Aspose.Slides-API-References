---
title: PreserveWhitespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, bewertet es, ob Leerzeichenknoten für den angegebenen Kontext beibehalten oder entfernt werden sollen.
type: docs
weight: 40
url: /de/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) Methode


When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Der Leerzeichenknoten, der im aktuellen Kontext beibehalten oder entfernt werden soll. |

### Rückgabewert

**true** wenn das Leerzeichen beibehalten werden soll; **false** wenn das Leerzeichen entfernt werden soll.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasse [XsltContext](../)
* Namensraum [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)