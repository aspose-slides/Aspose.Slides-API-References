---
title: GetAttributeNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'XmlAttribute con il nome specificato.
type: docs
weight: 248
url: /it/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) metodo

Restituisce il [XmlAttribute](../../xmlattribute/) con il nome specificato.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome dell'attributo da recuperare. Questo è un nome qualificato. Viene confrontato con il valore **get_Name** del nodo corrispondente. |

### Valore di ritorno

Il [XmlAttribute](../../xmlattribute/) specificato o **nullptr** se non è stato trovato un attributo corrispondente.

## XmlElement::GetAttributeNode(String, String) metodo

Restituisce il [XmlAttribute](../../xmlattribute/) con il nome locale e l'URI di namespace specificati.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI di namespace dell'attributo. |

### Valore di ritorno

Il [XmlAttribute](../../xmlattribute/) specificato o **nullptr** se non è stato trovato un attributo corrispondente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)