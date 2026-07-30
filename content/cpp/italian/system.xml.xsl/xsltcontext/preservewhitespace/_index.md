---
title: PreserveWhitespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, valuta se preservare i nodi di spazio bianco o rimuoverli per il contesto specificato.
type: docs
weight: 40
url: /it/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) metodo

When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Il nodo di spazio bianco che deve essere preservato o rimosso nel contesto corrente. |

### Valore di ritorno

**true** se lo spazio bianco deve essere preservato; **false** se lo spazio bianco deve essere rimosso.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Libreria [Aspose.Slides](../../../)