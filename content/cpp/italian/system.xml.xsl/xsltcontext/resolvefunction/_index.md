---
title: ResolveFunction()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, risolve un riferimento a funzione e restituisce un IXsltContextFunction che rappresenta la funzione. L'IXsltContextFunction viene utilizzato al momento dell'esecuzione per ottenere il valore di ritorno della funzione.
type: docs
weight: 27
url: /it/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) metodo


Quando viene sovrascritto in una classe derivata, risolve un riferimento a funzione e restituisce un [IXsltContextFunction](../../ixsltcontextfunction/) che rappresenta la funzione. Il [IXsltContextFunction](../../ixsltcontextfunction/) viene utilizzato al momento dell'esecuzione per ottenere il valore di ritorno della funzione.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Il prefisso della funzione così come appare nell'espressione [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Il nome della funzione. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Un array di tipi di argomento per la funzione da risolvere. Questo consente di scegliere tra metodi con lo stesso nome (ad esempio, metodi sovraccaricati). |

### Valore restituito

Un [IXsltContextFunction](../../ixsltcontextfunction/) che rappresenta la funzione.

## Vedi anche

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)