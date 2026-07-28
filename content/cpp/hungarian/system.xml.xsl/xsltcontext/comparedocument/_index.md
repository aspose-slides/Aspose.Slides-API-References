---
title: CompareDocument()
second_title: Aspose.Slides for C++ API Referencia
description: Amikor egy leszármaztatott osztályban felülírják, összehasonlítja a két dokumentum alap Uniform Resource Identifiers (URIs) értékét a dokumentumok XSLT processzor által betöltésének sorrendje alapján (azaz az XslTransform osztály).
type: docs
weight: 53
url: /hu/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) metódus


Amikor egy leszármaztatott osztályban felülírják, összehasonlítja a két dokumentum alap Uniform Resource Identifiers (URI)-jait a dokumentumok XSLT processzor által betöltésének sorrendje alapján (azaz a [XslTransform](../../xsltransform/) osztály).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Az első összehasonlítandó dokumentum alap URI-ja. |
| nextbaseUri | [String](../../../system/string/) | A második összehasonlítandó dokumentum alap URI-ja. |

### Visszatérési érték

Egy egész szám, ami leírja a két alap URI relatív sorrendjét: -1, ha **baseUri** előtt jelenik meg **nextbaseUri**; 0, ha a két alap URI azonos; és 1, ha **baseUri** után jelenik meg **nextbaseUri**.

## Kapcsolódó információk

* Osztály [String](../../../system/string/)
* Osztály [XsltContext](../)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)