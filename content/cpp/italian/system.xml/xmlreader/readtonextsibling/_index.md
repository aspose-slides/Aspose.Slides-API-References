---
title: ReadToNextSibling()
second_title: Riferimento API di Aspose.Slides per C++
description: Avanza l'XmlReader al prossimo elemento fratello con il nome qualificato specificato.
type: docs
weight: 924
url: /it/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) metodo

Avanza il [XmlReader](../) al prossimo elemento fratello con il nome qualificato specificato.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'elemento fratello a cui si desidera spostare. |

### Valore restituito

**true** se viene trovato un elemento fratello corrispondente; altrimenti **false**. Se non viene trovato un elemento fratello corrispondente, il [XmlReader](../) è posizionato sul tag di chiusura (il valore [XmlReader::get_NodeType](../get_nodetype/) è [XmlNodeType::EndElement](../../xmlnodetype/)) dell'elemento genitore.

## XmlReader::ReadToNextSibling(String, String) metodo

Avanza il [XmlReader](../) al prossimo elemento fratello con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento fratello a cui si desidera spostare. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento fratello a cui si desidera spostare. |

### Valore restituito

**true** se viene trovato un elemento fratello corrispondente; altrimenti **false**. Se non viene trovato un elemento fratello corrispondente, il [XmlReader](../) è posizionato sul tag di chiusura (il valore [XmlReader::get_NodeType](../get_nodetype/) è [XmlNodeType::EndElement](../../xmlnodetype/)) dell'elemento genitore.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)