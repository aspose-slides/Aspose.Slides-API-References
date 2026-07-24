---
title: Read()
second_title: Aspose.Slides für C++ API Referenz
description: Liest ein einzelnes Zeichen aus dem Stream.
type: docs
weight: 40
url: /de/system.io/streamreader/read/
---
## StreamReader::Read() Methode


Liest ein einzelnes Zeichen aus dem Stream.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Rückgabewert

Gelesenes Zeichen, kodiert mit UTF-16; falls das gelesene Zeichen in UTF-16 durch zwei Codepoints dargestellt wird, wird nur das hochwertige Surrogat zurückgegeben.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) Methode


Liest die angegebene Anzahl von Zeichen aus dem Stream, konvertiert sie in UTF-16-Kodierung und schreibt die resultierenden UTF-16-Zeichen in das angegebene Zeichenarray, beginnend an der angegebenen Position.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Das UTF-16-Zeichenarray, in das die aus dem Stream gelesenen Zeichen geschrieben werden |
| index | int | Ein nullbasierter Index im **buffer**, an dem das Schreiben beginnt |
| count | int | Die Anzahl der Zeichen, die aus dem Stream gelesen werden sollen |

### Rückgabewert

Die Anzahl der aus dem Stream gelesenen Zeichen

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StreamReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)