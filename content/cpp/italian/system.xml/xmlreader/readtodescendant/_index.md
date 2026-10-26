---
title: ReadToDescendant()
second_title: Riferimento API di Aspose.Slides per C++
description: Avanza l'XmlReader al prossimo elemento discendente con il nome qualificato specificato.
type: docs
weight: 911
url: /it/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) metodo

Avanza il [XmlReader](../) al prossimo elemento discendente con il nome qualificato specificato.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'elemento a cui si desidera spostarsi. |

### Valore restituito

**true** se viene trovato un elemento discendente corrispondente; altrimenti **false**. Se non viene trovato un elemento figlio corrispondente, il [XmlReader](../) è posizionato sul tag di chiusura (il valore [XmlReader::get_NodeType](../get_nodetype/) è [XmlNodeType::EndElement](../../xmlnodetype/)) dell'elemento. Se il [XmlReader](../) non è posizionato su un elemento quando [XmlReader::ReadToDescendant(String)](./) è stato chiamato, questo metodo restituisce **false** e la posizione del [XmlReader](../) non viene modificata.

## XmlReader::ReadToDescendant(String, String) metodo

Avanza il [XmlReader](../) al prossimo elemento discendente con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento a cui si desidera spostarsi. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento a cui si desidera spostarsi. |

### Valore restituito

**true** se viene trovato un elemento discendente corrispondente; altrimenti **false**. Se non viene trovato un elemento figlio corrispondente, il [XmlReader](../) è posizionato sul tag di chiusura (il valore [XmlReader::get_NodeType](../get_nodetype/) è [XmlNodeType::EndElement](../../xmlnodetype/)) dell'elemento. Se il [XmlReader](../) non è posizionato su un elemento quando [XmlReader::ReadToDescendant(String,String)](./) è stato chiamato, questo metodo restituisce **false** e la posizione del [XmlReader](../) non viene modificata.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)