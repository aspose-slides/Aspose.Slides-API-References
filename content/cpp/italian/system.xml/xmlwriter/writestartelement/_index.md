---
title: WriteStartElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, scrive il tag di apertura specificato e lo associa allo spazio dei nomi fornito.
type: docs
weight: 92
url: /it/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) metodo


Quando sovrascritto in una classe derivata, scrive il tag di apertura specificato e lo associa allo spazio dei nomi fornito.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'elemento. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi da associare all'elemento. Se questo spazio dei nomi è già in ambito e ha un prefisso associato, lo scrittore inserisce automaticamente anche quel prefisso. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) metodo


Quando sovrascritto in una classe derivata, scrive il tag di apertura specificato e lo associa allo spazio dei nomi e al prefisso forniti.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso dello spazio dei nomi dell'elemento. |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'elemento. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi da associare all'elemento. |

## XmlWriter::WriteStartElement(const String\&) metodo


Quando sovrascritto in una classe derivata, scrive un tag di apertura con il nome locale specificato.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'elemento. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)