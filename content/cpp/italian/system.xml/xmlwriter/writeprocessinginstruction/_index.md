---
title: WriteProcessingInstruction()
second_title: Riferimento API di Aspose.Slides per C++
description: "Quando viene sovrascritto in una classe derivata, scrive un'istruzione di elaborazione con uno spazio tra il nome e il testo come segue: <?name text?>."
type: docs
weight: 196
url: /it/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) metodo

Quando viene sovrascritto in una classe derivata, scrive un'istruzione di elaborazione con uno spazio tra il nome e il testo come segue: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome dell'istruzione di elaborazione. |
| text | [String](../../../system/string/) | Il testo da includere nell'istruzione di elaborazione. |
## Osservazioni

Questo metodo viene utilizzato per creare una dichiarazione XML dopo che [XmlWriter::WriteStartDocument](../writestartdocument/) è già stato chiamato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)