---
title: HasAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se il nodo corrente ha un attributo con il nome specificato.
type: docs
weight: 300
url: /it/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) metodo

Determina se il nodo corrente ha un attributo con il nome specificato.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome dell'attributo da trovare. Questo è un nome qualificato. Viene confrontato con il valore **get_Name** del nodo corrispondente. |

### Valore di ritorno

**true** se il nodo corrente ha l'attributo specificato; altrimenti, **false**.

## XmlElement::HasAttribute(String, String) metodo

Determina se il nodo corrente ha un attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo da trovare. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo da trovare. |

### Valore di ritorno

**true** se il nodo corrente ha l'attributo specificato; altrimenti, **false**.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)