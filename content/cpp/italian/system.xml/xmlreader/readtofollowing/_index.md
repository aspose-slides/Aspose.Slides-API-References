---
title: ReadToFollowing()
second_title: Riferimento API Aspose.Slides per C++
description: Legge fino a quando non viene trovato un elemento con il nome qualificato specificato.
type: docs
weight: 898
url: /it/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) metodo


Legge fino a quando non viene trovato un elemento con il nome qualificato specificato.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the element. |

### Valore di ritorno

**true** se è stato trovato un elemento corrispondente; altrimenti **false** e il [XmlReader](../) si trova in stato di fine file.

## XmlReader::ReadToFollowing(String, String) metodo


Legge fino a quando non viene trovato un elemento con il nome locale e l'URI di namespace specificati.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento. |
| namespaceURI | [String](../../../system/string/) | L'URI di namespace dell'elemento. |

### Valore di ritorno

**true** se è stato trovato un elemento corrispondente; altrimenti **false** e il [XmlReader](../) si trova in stato di fine file.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)