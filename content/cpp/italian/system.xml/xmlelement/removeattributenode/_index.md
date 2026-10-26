---
title: RemoveAttributeNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'XmlAttribute specificato.
type: docs
weight: 274
url: /it/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) metodo


Rimuove il/la [XmlAttribute](../../xmlattribute/) specificato.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Il nodo [XmlAttribute](../../xmlattribute/) da rimuovere. Se l'attributo rimosso ha un valore predefinito, viene immediatamente sostituito. |

### Valore di ritorno

Il [XmlAttribute](../../xmlattribute/) rimosso o **nullptr** se **oldAttr** non è un nodo attributo del [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) metodo


Rimuove il/la [XmlAttribute](../../xmlattribute/) specificato dal nome locale e dall'URI dello spazio dei nomi. (Se l'attributo rimosso ha un valore predefinito, viene immediatamente sostituito).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

Il [XmlAttribute](../../xmlattribute/) rimosso o **nullptr** se il [XmlElement](../) non possiede un nodo attributo corrispondente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)