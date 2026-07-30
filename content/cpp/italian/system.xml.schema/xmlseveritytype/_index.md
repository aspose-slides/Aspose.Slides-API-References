---
title: XmlSeverityType
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta la gravità dell'evento di convalida.
type: docs
weight: 1080
url: /it/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Rappresenta la gravità dell'evento di convalida.

```cpp
enum class XmlSeverityType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Error | 0 | Indica che si è verificato un errore di convalida durante la convalida del documento di istanza. Questo si applica alle definizioni di tipo di documento (DTDs) e agli schemi XML [Schema](../) definition language (XSD). Le restrizioni di validità del World Wide [Web](../../system.web/) Consortium (W3C) sono considerate errori. Se non è stato creato alcun gestore di eventi di convalida, gli errori generano un'eccezione. |
| Warning | 1 | Indica che si è verificato un evento di convalida che non è un errore. Un avviso viene tipicamente emesso quando non è presente un DTD o XML [Schema](../) per convalidare un elemento o attributo specifico. A differenza degli errori, gli avvisi non generano un'eccezione se non esiste un gestore di eventi di convalida. |

## Vedi anche

* Spazio dei nomi [System::Xml::Schema](../)
* Libreria [Aspose.Slides](../../)