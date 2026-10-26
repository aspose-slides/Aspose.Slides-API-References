---
title: GetAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore dell'attributo con il nome specificato.
type: docs
weight: 209
url: /it/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) metodo


Restituisce il valore dell'attributo con il nome specificato.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome dell'attributo da recuperare. Questo è un nome qualificato. Viene confrontato con il valore **get_Name** del nodo corrispondente. |

### Valore di ritorno

Il valore dell'attributo specificato. Viene restituita una stringa vuota se non si trova un attributo corrispondente o se l'attributo non ha un valore specificato o predefinito.

## XmlElement::GetAttribute(String, String) metodo


Restituisce il valore dell'attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo da recuperare. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo da recuperare. |

### Valore di ritorno

Il valore dell'attributo specificato. Viene restituita una stringa vuota se non si trova un attributo corrispondente o se l'attributo non ha un valore specificato o predefinito.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)