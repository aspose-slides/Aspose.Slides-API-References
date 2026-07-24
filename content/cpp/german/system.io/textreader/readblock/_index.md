---
title: ReadBlock()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die angegebene maximale Anzahl von Zeichen aus dem aktuellen Textleser und schreibt die Daten in einen Puffer, beginnend bei dem angegebenen Index.
type: docs
weight: 53
url: /de/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) Methode

Liest die angegebene maximale Zeichenanzahl aus dem aktuellen Textleser und schreibt die Daten in einen Puffer, beginnend bei dem angegebenen Index.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Ein Zeichenpuffer, in den die gelesenen Daten geschrieben werden |
| index | int | Ein 0-basierter Index im **buffer**, an dem das Schreiben beginnt |
| count | int | Die maximale Anzahl zu lesender Zeichen |

### Rückgabewert

Die tatsächlich gelesene Zeichenanzahl

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [TextReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)