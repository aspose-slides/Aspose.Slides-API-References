---
title: ResolveFunction()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird in einer abgeleiteten Klasse überschrieben, löst einen Funktionsverweis auf und gibt ein IXsltContextFunction zurück, das die Funktion darstellt. Das IXsltContextFunction wird zur Ausführungszeit verwendet, um den Rückgabewert der Funktion zu erhalten.
type: docs
weight: 27
url: /de/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) Methode


Wenn in einer abgeleiteten Klasse überschrieben, löst es einen Funktionsverweis auf und gibt ein [IXsltContextFunction](../../ixsltcontextfunction/) zurück, das die Funktion darstellt. Das [IXsltContextFunction](../../ixsltcontextfunction/) wird zur Laufzeit verwendet, um den Rückgabewert der Funktion zu erhalten.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Der Präfix der Funktion, wie er im [XPath](../../../system.xml.xpath/) Ausdruck erscheint. |
| name | [String](../../../system/string/) | Der Name der Funktion. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Ein Array von Argumenttypen für die aufgelöste Funktion. Dadurch können Sie zwischen Methoden mit demselben Namen wählen (z. B. überladene Methoden). |

### Rückgabewert

Ein [IXsltContextFunction](../../ixsltcontextfunction/), das die Funktion darstellt.

## Siehe auch

* Aufzählung [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klasse [IXsltContextFunction](../../ixsltcontextfunction/)
* Klasse [String](../../../system/string/)
* Klasse [XsltContext](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)