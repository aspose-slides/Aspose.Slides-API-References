---
title: WriteProcessingInstruction()
second_title: Riferimento API Aspose.Slides per C++
description: "Scrive un'istruzione di elaborazione con uno spazio tra il nome e il testo come segue: <?name text?>."
type: docs
weight: 326
url: /it/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) metodo

Scrive un'istruzione di elaborazione con uno spazio tra il nome e il testo come segue: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome dell'istruzione di elaborazione. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) da includere nell'istruzione di elaborazione. |

## Osservazioni

Questo metodo viene utilizzato per creare una dichiarazione XML dopo che [XmlTextWriter::WriteStartDocument](../writestartdocument/) è già stata chiamata.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)