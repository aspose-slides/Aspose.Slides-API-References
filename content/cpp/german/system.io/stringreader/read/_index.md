---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest ein einzelnes Zeichen aus dem Stream.
type: docs
weight: 40
url: /de/system.io/stringreader/read/
---
## StringReader::Read() Methode

Liest ein einzelnes Zeichen aus dem Stream.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Rückgabewert

Ein gelesenes Zeichen oder -1, wenn kein Zeichen gelesen wurde

## StringReader::Read(ArrayPtr\<char_t\>, int, int) Methode

Liest die angegebene Anzahl von Zeichen aus dem Stream in das angegebene Zeichenarray, beginnend an der angegebenen Position.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Das Zeichenarray, in das die aus dem Stream gelesenen Zeichen geschrieben werden |
| index | int | Ein nullbasierter Index in **buffer**, an dem das Schreiben beginnt |
| count | int | Die Anzahl der aus dem Stream zu lesenden Zeichen |

### Rückgabewert

Die Anzahl der aus dem Stream gelesenen Zeichen

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StringReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)