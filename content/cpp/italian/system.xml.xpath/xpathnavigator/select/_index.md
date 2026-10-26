---
title: Select()
second_title: Riferimento API di Aspose.Slides per C++
description: Seleziona un insieme di nodi, utilizzando l'espressione XPath specificata.
type: docs
weight: 794
url: /it/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) metodo

Seleziona un insieme di nodi, utilizzando l'espressione [XPath](../../) specificata.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) che rappresenta un'espressione [XPath](../../). |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che punta all'insieme di nodi selezionato.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) metodo

Seleziona un insieme di nodi utilizzando l'espressione [XPath](../../) specificata con l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi di spazio dei nomi.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) che rappresenta un'espressione [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere i prefissi di spazio dei nomi. |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che punta all'insieme di nodi selezionato.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) metodo

Seleziona un insieme di nodi utilizzando il [XPathExpression](../../xpathexpression/) specificato.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un oggetto [XPathExpression](../../xpathexpression/) contenente la query [XPath](../../) compilata. |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che punta all'insieme di nodi selezionato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)