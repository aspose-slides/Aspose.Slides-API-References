---
title: WriteStartElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive il tag di inizio specificato e lo associa allo spazio dei nomi e al prefisso forniti.
type: docs
weight: 235
url: /it/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) metodo

Scrive il tag di inizio specificato e lo associa allo spazio dei nomi e al prefisso forniti.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso di spazio dei nomi dell'elemento. |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'elemento. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi da associare all'elemento. Se questo spazio dei nomi è già in ambito e ha un prefisso associato, lo scrittore scrive automaticamente anche quel prefisso. |

## Vedere anche

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)