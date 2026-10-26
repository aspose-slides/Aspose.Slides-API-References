---
title: SetAttributeNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge lo XmlAttribute specificato.
type: docs
weight: 261
url: /it/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Aggiunge il [XmlAttribute](../../xmlattribute/) specificato.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Il nodo [XmlAttribute](../../xmlattribute/) da aggiungere alla raccolta di attributi per questo elemento. |

### Valore di ritorno

Se l'attributo sostituisce un attributo esistente con lo stesso nome, il vecchio [XmlAttribute](../../xmlattribute/) viene restituito; altrimenti, **nullptr** è restituito.

## XmlElement::SetAttributeNode(String, String) method


Aggiunge il [XmlAttribute](../../xmlattribute/) specificato.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI del namespace dell'attributo. |

### Valore di ritorno

Il [XmlAttribute](../../xmlattribute/) da aggiungere.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlElement](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)