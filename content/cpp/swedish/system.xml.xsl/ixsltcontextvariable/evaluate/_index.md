---
title: Evaluate()
second_title: Aspose.Slides för C++ API-referens
description: Utvärderar variabeln vid körning och returnerar ett objekt som representerar variabelns värde.
type: docs
weight: 40
url: /sv/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) metod


Utvärderar variabeln vid körning och returnerar ett objekt som representerar variabelns värde.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Ett [XsltContext](../../xsltcontext/) som representerar variabelns exekveringskontext. |

### Returvärde

Ett [Object](../../../system/object/) som representerar variabelns värde. Möjliga returtyper inkluderar number, string, [Boolean](../../../system/boolean/), dokumentfragment eller nodmängd.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [XsltContext](../../xsltcontext/)
* Klass [IXsltContextVariable](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)