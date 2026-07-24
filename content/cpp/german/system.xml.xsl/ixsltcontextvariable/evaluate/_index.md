---
title: Evaluate()
second_title: Aspose.Slides für C++ API-Referenz
description: Bewertet die Variable zur Laufzeit und gibt ein Objekt zurück, das den Wert der Variable darstellt.
type: docs
weight: 40
url: /de/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) Methode

Bewertet die Variable zur Laufzeit und gibt ein Objekt zurück, das den Wert der Variable darstellt.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Ein [XsltContext](../../xsltcontext/), der den Ausführungskontext der Variable darstellt. |

### Rückgabewert

Ein [Object](../../../system/object/) der den Wert der Variable darstellt. Mögliche Rückgabetypen umfassen number, string, [Boolean](../../../system/boolean/), document fragment oder node set.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XsltContext](../../xsltcontext/)
* Klasse [IXsltContextVariable](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)