---
title: ToBase64CharArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und speichert die codierten Daten als ein Array von Unicode-Zeichen.
type: docs
weight: 27
url: /de/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) Methode

Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und speichert die codierten Daten als ein Array von Unicode-Zeichen.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Das Array von Bytes, das den zu kodierenden Bereich von Elementen enthält |
| offset_in | int | Ein Index eines Elements im Eingabearray, an dem der zu kodierende Bereich beginnt |
| length | int | Die Länge des zu kodierenden Elementbereichs |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Eine konstante Referenz auf das Ausgangsarray, in das die resultierenden Daten geschrieben werden sollen |
| offset_out | int | Ein Index im Ausgangsarray, an dem das Schreiben der resultierenden Daten beginnen soll |
| insert_line_breaks | **bool** | Gibt an, ob Zeilenumbruchzeichen nach jeweils 76 Base-64-Zeichen in das Ausgangsarray eingefügt werden sollen |

### Rückgabewert

Die Anzahl der in das Ausgangsarray geschriebenen Zeichen

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) Methode

Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und speichert die codierten Daten als ein Array von Unicode-Zeichen.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Das Array von Bytes, das den zu kodierenden Bereich von Elementen enthält |
| offset_in | int | Ein Index eines Elements im Eingabearray, an dem der zu kodierende Bereich beginnt |
| length | int | Die Länge des zu kodierenden Elementbereichs |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Eine konstante Referenz auf das Ausgangsarray, in das die resultierenden Daten geschrieben werden sollen |
| offset_out | int | Ein Index im Ausgangsarray, an dem das Schreiben der resultierenden Daten beginnen soll |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Gibt die Formatierungsoptionen für Base-64-kodierte Daten an |

### Rückgabewert

Die Anzahl der in das Ausgangsarray geschriebenen Zeichen

## Siehe auch

* Aufzählung [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struktur [Convert](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)