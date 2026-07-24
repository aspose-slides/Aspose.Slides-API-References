---
title: CompareDocument()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, vergleicht sie die Basis Uniform Resource Identifiers (URIs) von zwei Dokumenten basierend auf der Reihenfolge, in der die Dokumente vom XSLT-Prozessor geladen wurden (das ist die XslTransform-Klasse).
type: docs
weight: 53
url: /de/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) Methode

When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the [XslTransform](../../xsltransform/) class).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Der Basis-URI des ersten zu vergleichenden Dokuments. |
| nextbaseUri | [String](../../../system/string/) | Der Basis-URI des zweiten zu vergleichenden Dokuments. |

### Rückgabewert

Ein Ganzzahlwert, der die relative Reihenfolge der beiden Basis-URIs beschreibt: -1, wenn **baseUri** vor **nextbaseUri** vorkommt; 0, wenn die beiden Basis-URIs identisch sind; und 1, wenn **baseUri** nach **nextbaseUri** vorkommt.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XsltContext](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)