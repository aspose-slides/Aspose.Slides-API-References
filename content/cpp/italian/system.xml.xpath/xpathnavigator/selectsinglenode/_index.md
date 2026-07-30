---
title: SelectSingleNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Seleziona un nodo singolo nel XPathNavigator utilizzando la query XPath specificata.
type: docs
weight: 781
url: /it/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metodo


Seleziona un nodo singolo nel [XPathNavigator](../) utilizzando la query [XPath](../../) specificata.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) che rappresenta un'espressione [XPath](../../). |

### Valore di ritorno

Un oggetto [XPathNavigator](../) che contiene il primo nodo corrispondente per la query [XPath](../../) specificata; altrimenti, **nullptr** se non ci sono risultati della query.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metodo


Seleziona un nodo singolo nell'oggetto [XPathNavigator](../) utilizzando la query [XPath](../../) specificata con l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indicato per risolvere i prefissi degli spazi dei nomi.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) che rappresenta un'espressione [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere i prefissi degli spazi dei nomi nella query [XPath](../../). |

### Valore di ritorno

Un oggetto [XPathNavigator](../) che contiene il primo nodo corrispondente per la query [XPath](../../) specificata; altrimenti **nullptr** se non ci sono risultati della query.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metodo


Seleziona un nodo singolo nel [XPathNavigator](../) utilizzando l'oggetto [XPathExpression](../../xpathexpression/) specificato.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) contenente la query [XPath](../../) compilata. |

### Valore di ritorno

Un oggetto [XPathNavigator](../) che contiene il primo nodo corrispondente per la query [XPath](../../) specificata; altrimenti **nullptr** se non ci sono risultati della query.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathExpression](../../xpathexpression/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)