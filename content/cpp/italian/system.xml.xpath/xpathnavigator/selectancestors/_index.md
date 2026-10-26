---
title: SelectAncestors()
second_title: Riferimento API di Aspose.Slides per C++
description: Seleziona tutti i nodi antenati del nodo corrente che hanno un XPathNodeType corrispondente.
type: docs
weight: 846
url: /it/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metodo


Seleziona tutti i nodi antenati del nodo corrente che hanno un XPathNodeType corrispondente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Il XPathNodeType dei nodi antenati. |
| matchSelf | **bool** | Per includere il nodo di contesto nella selezione, **true**; altrimenti, **false**. |

### Valore restituito

Un [XPathNodeIterator](../../xpathnodeiterator/) che contiene i nodi selezionati. I nodi restituiti sono in ordine inverso del documento.

## XPathNavigator::SelectAncestors(String, String, bool) metodo


Seleziona tutti i nodi antenati del nodo corrente che hanno il nome locale e l'URI di namespace specificati.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dei nodi antenati. |
| namespaceURI | [String](../../../system/string/) | L'URI di namespace dei nodi antenati. |
| matchSelf | **bool** | Per includere il nodo di contesto nella selezione, **true**; altrimenti, **false**. |

### Valore restituito

Un [XPathNodeIterator](../../xpathnodeiterator/) che contiene i nodi selezionati. I nodi restituiti sono in ordine inverso del documento.

## Vedi anche

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)