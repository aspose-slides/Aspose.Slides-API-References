---
title: Evaluate()
second_title: Riferimento API di Aspose.Slides per C++
description: Valuta l'espressione XPath specificata e restituisce il risultato tipizzato.
type: docs
weight: 807
url: /it/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) metodo


Valuta l'espressione [XPath](../../) specificata e restituisce il risultato tipizzato.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Una stringa che rappresenta un'espressione [XPath](../../) che può essere valutata. |

### Valore restituito

Il risultato dell'espressione ([Boolean](../../../system/boolean/), numero, stringa o insieme di nodi). Questo corrisponde rispettivamente agli oggetti [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) metodo


Valuta l'espressione [XPath](../../) specificata e restituisce il risultato tipizzato, usando l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi di namespace nell'espressione [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Una stringa che rappresenta un'espressione [XPath](../../) che può essere valutata. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere i prefissi di namespace nell'espressione [XPath](../../). |

### Valore restituito

Il risultato dell'espressione ([Boolean](../../../system/boolean/), numero, stringa o insieme di nodi). Questo corrisponde rispettivamente agli oggetti [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) metodo


Valuta il [XPathExpression](../../xpathexpression/) e restituisce il risultato tipizzato.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) che può essere valutato. |

### Valore restituito

Il risultato dell'espressione ([Boolean](../../../system/boolean/), numero, stringa o insieme di nodi). Questo corrisponde rispettivamente agli oggetti [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) metodo


Usa il contesto fornito per valutare il [XPathExpression](../../xpathexpression/) e restituisce il risultato tipizzato.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) che può essere valutato. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Un [XPathNodeIterator](../../xpathnodeiterator/) che punta all'insieme di nodi selezionato su cui eseguire la valutazione. |

### Valore restituito

Il risultato dell'espressione ([Boolean](../../../system/boolean/), numero, stringa o insieme di nodi). Questo corrisponde rispettivamente agli oggetti [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathExpression](../../xpathexpression/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Namespace [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)