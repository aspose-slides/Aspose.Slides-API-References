---
title: SelectSingleNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Seleziona il primo XmlNode che corrisponde all'espressione XPath.
type: docs
weight: 352
url: /it/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) metodo

Seleziona il primo [XmlNode](../) che corrisponde all'espressione [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'espressione [XPath](../../../system.xml.xpath/). |

### Valore di ritorno

Il primo [XmlNode](../) che corrisponde alla query [XPath](../../../system.xml.xpath/) o **nullptr** se non viene trovato alcun nodo corrispondente.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metodo

Seleziona il primo [XmlNode](../) che corrisponde all'espressione [XPath](../../../system.xml.xpath/). Qualsiasi prefisso trovato nell'espressione [XPath](../../../system.xml.xpath/) viene risolto usando il [XmlNamespaceManager](../../xmlnamespacemanager/) fornito.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'espressione [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) da usare per risolvere gli spazi dei nomi dei prefissi nell'espressione [XPath](../../../system.xml.xpath/). |

### Valore di ritorno

Il primo [XmlNode](../) che corrisponde alla query [XPath](../../../system.xml.xpath/) o **nullptr** se non viene trovato alcun nodo corrispondente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)