---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest ein einzelnes Zeichen aus dem Stream.
type: docs
weight: 40
url: /de/system.io/textreader/read/
---
## TextReader::Read() Methode


Liest ein einzelnes Zeichen aus dem Stream.

```cpp
virtual int System::IO::TextReader::Read()
```


### Rückgabewert

Gelesenes Zeichen, codiert mit UTF-16; falls das gelesene Zeichen durch zwei Codepunkte in UTF-16 dargestellt wird, wird nur das hohe Surrogat zurückgegeben.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) Methode


Liest die angegebene Anzahl von Zeichen aus dem Stream und schreibt sie in das angegebene Zeichenarray, beginnend an der angegebenen Position.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Das UTF-16 Zeichenarray, in das die aus dem Stream gelesenen Zeichen geschrieben werden |
| index | int | Ein nullbasierter Index in **buffer**, an dem das Schreiben beginnt |
| count | int | Die Anzahl der aus dem Stream zu lesenden Zeichen |

### Rückgabewert

Die Anzahl der aus dem Stream gelesenen Zeichen

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [TextReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)