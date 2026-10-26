---
title: SelectDescendants()
second_title: Riferimento API di Aspose.Slides per C++
description: Seleziona tutti i nodi discendenti del nodo corrente che hanno un XPathNodeType corrispondente.
type: docs
weight: 859
url: /it/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) metodo


Seleziona tutti i nodi discendenti del nodo corrente che hanno un XPathNodeType corrispondente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | L'XPathNodeType dei nodi discendenti. |
| matchSelf | **bool** | **true** per includere il nodo di contesto nella selezione; altrimenti, **false**. |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che contiene i nodi selezionati.

## XPathNavigator::SelectDescendants(String, String, bool) metodo


Seleziona tutti i nodi discendenti del nodo corrente con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dei nodi discendenti. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dei nodi discendenti. |
| matchSelf | **bool** | **true** per includere il nodo di contesto nella selezione; altrimenti, **false**. |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che contiene i nodi selezionati.

## Vedi anche

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)