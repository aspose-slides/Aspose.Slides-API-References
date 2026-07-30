---
title: CompareDocument()
second_title: Aspose.Slides pro C++ API Reference
description: Když je přepsána v odvozené třídě, porovná základní Uniform Resource Identifiers (URIs) dvou dokumentů na základě pořadí, v jakém byly dokumenty načteny procesorem XSLT (tedy třída XslTransform).
type: docs
weight: 53
url: /cs/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) metoda


Když je přepsána v odvozené třídě, porovná základní Uniform Resource Identifiers (URIs) dvou dokumentů podle pořadí, v jakém byly dokumenty načteny procesorem XSLT (tj. třída [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Základní URI prvního dokumentu pro porovnání. |
| nextbaseUri | [String](../../../system/string/) | Základní URI druhého dokumentu pro porovnání. |

### Návratová hodnota

Celé číslo popisující relativní pořadí dvou základních URI: -1 pokud **baseUri** nastává před **nextbaseUri**; 0 pokud jsou oba základní URI identické; a 1 pokud **baseUri** nastává po **nextbaseUri**.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XsltContext](../)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)