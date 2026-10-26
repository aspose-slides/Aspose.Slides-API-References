---
title: Invoke()
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce il metodo per invocare la funzione con gli argomenti forniti nel contesto specificato.
type: docs
weight: 53
url: /it/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

Fornisce il metodo per invocare la funzione con gli argomenti forniti nel contesto specificato.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Il contesto XSLT per la chiamata della funzione. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Gli argomenti della chiamata della funzione. Ogni argomento è un elemento dell'array. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Il nodo di contesto per la chiamata della funzione. |

### Valore di ritorno

Un [Object](../../../system/object/) che rappresenta il valore di ritorno della funzione.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [XsltContext](../../xsltcontext/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)