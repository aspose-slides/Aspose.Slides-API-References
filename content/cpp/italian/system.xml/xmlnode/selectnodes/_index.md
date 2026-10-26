---
title: SelectNodes()
second_title: Riferimento API di Aspose.Slides per C++
description: Seleziona un elenco di nodi corrispondenti all'espressione XPath.
type: docs
weight: 365
url: /it/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) metodo

Seleziona un elenco di nodi corrispondenti all'espressione [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'espressione [XPath](../../../system.xml.xpath/). |

### Valore di ritorno

Un [XmlNodeList](../../xmlnodelist/) contenente una raccolta di nodi che corrispondono alla query [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metodo

Seleziona un elenco di nodi corrispondenti all'espressione [XPath](../../../system.xml.xpath/). Eventuali prefissi trovati nell'espressione [XPath](../../../system.xml.xpath/) vengono risolti utilizzando il [XmlNamespaceManager](../../xmlnamespacemanager/) fornito.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'espressione [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) da utilizzare per la risoluzione degli spazi dei nomi per i prefissi nell'espressione [XPath](../../../system.xml.xpath/). |

### Valore di ritorno

Un [XmlNodeList](../../xmlnodelist/) contenente una raccolta di nodi che corrispondono alla query [XPath](../../../system.xml.xpath/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Classe [XmlNamespaceManager](../../xmlnamespacemanager/)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)