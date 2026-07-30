---
title: RemoveAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove un attributo per nome.
type: docs
weight: 235
url: /it/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) metodo


Rimuove un attributo per nome.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome dell'attributo da rimuovere. Questo è un nome qualificato. Viene confrontato con il valore **get_Name** del nodo corrispondente. |

## XmlElement::RemoveAttribute(String, String) metodo


Rimuove un attributo con il nome locale e l'URI dello spazio dei nomi specificati. (Se l'attributo rimosso ha un valore predefinito, viene immediatamente sostituito).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo da rimuovere. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo da rimuovere. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)