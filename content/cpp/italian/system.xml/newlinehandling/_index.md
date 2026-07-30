---
title: NewLineHandling
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come gestire le interruzioni di riga.
type: docs
weight: 690
url: /it/system.xml/newlinehandling/
---
## NewLineHandling enum

Specifica come gestire le interruzioni di riga.

```cpp
enum class NewLineHandling
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Replace | 0 | I caratteri di nuova linea vengono sostituiti per corrispondere al carattere specificato nel valore [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | I caratteri di nuova linea vengono entizzati. Questa impostazione conserva tutti i caratteri quando l'output viene letto da un [XmlReader](../xmlreader/) normalizzante. |
| None | 2 | I caratteri di nuova linea rimangono invariati. L'output è lo stesso dell'input. |

## Vedi anche

* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)