---
title: SelectChildren()
second_title: Riferimento API Aspose.Slides per C++
description: Seleziona tutti i nodi figli del nodo corrente che hanno il tipo XPathNodeType corrispondente.
type: docs
weight: 833
url: /it/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) metodo

Seleziona tutti i nodi figlio del nodo corrente che hanno il tipo XPathNodeType corrispondente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Il tipo XPathNodeType dei nodi figlio. |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che contiene i nodi selezionati.

## XPathNavigator::SelectChildren(String, String) metodo

Seleziona tutti i nodi figlio del nodo corrente che hanno il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dei nodi figlio. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dei nodi figlio. |

### Valore di ritorno

Un [XPathNodeIterator](../../xpathnodeiterator/) che contiene i nodi selezionati.

## Vedi anche

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)