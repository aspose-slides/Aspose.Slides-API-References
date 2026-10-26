---
title: CompareDocument()
second_title: Aspose.Slides för C++ API-referens
description: När den överskuggas i en avledd klass jämför den bas Uniform Resource Identifiers (URIs) för två dokument baserat på den ordning i vilken dokumenten laddades av XSLT-processorn (that is, the XslTransform class).
type: docs
weight: 53
url: /sv/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) metod


När den överskuggas i en avledd klass jämför den bas-Uniform Resource Identifiers (URI:er) för två dokument baserat på den ordning i vilken dokumenten laddades av XSLT-processorn (det vill säga [XslTransform](../../xsltransform/)-klassen).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Bas-URI:n för det första dokumentet att jämföra. |
| nextbaseUri | [String](../../../system/string/) | Bas-URI:n för det andra dokumentet att jämföra. |

### Returvärde

Ett heltalsvärde som beskriver den relativa ordningen för de två bas-URI:erna: -1 om **baseUri** kommer före **nextbaseUri**; 0 om de två bas-URI:erna är identiska; och 1 om **baseUri** kommer efter **nextbaseUri**.

## Se även

* Klass [String](../../../system/string/)
* Klass [XsltContext](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)