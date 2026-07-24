---
title: ToBase64String()
second_title: Aspose.Slides für C++ API-Referenz
description: Base-64 codiert Elemente im angegebenen Byte-Array und gibt die kodierten Daten als Zeichenkette zurück.
type: docs
weight: 40
url: /de/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) Methode


Base-64 codiert die Elemente im angegebenen Byte-Array und gibt die codierten Daten als Zeichenkette zurück.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Das Array von Bytes zum Codieren |
| insert_line_breaks | **bool** | Gibt an, ob Zeilenumbruchzeichen nach jeweils 76 Base-64-Zeichen in die Ausgabekette eingefügt werden sollen |

### Rückgabewert

Die Zeichenkette, die die Base-64-kodierte Darstellung des Eingabearrays enthält

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) Methode


Base-64 codiert einen Bereich von Elementen im angegebenen Byte-Array und gibt die codierten Daten als Zeichenkette zurück.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Das Array von Bytes, das den zu kodierenden Elementbereich enthält |
| offset_in | int | Ein Index eines Elements im Eingabearray, an dem der zu kodierende Bereich beginnt |
| length | int | Die Länge des zu kodierenden Elementbereichs |
| insert_line_breaks | **bool** | Gibt an, ob Zeilenumbruchzeichen nach jeweils 76 Base-64-Zeichen in die Ausgabekette eingefügt werden sollen |

### Rückgabewert

Die Zeichenkette, die die Base-64-kodierte Darstellung des gewünschten Bereichs des Eingabearrays enthält

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) Methode


Base-64 codiert die Elemente im angegebenen Byte-Array und gibt die codierten Daten als Zeichenkette zurück.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Das Array von Bytes zum Codieren |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Gibt Formatierungsoptionen für die Base-64-kodierten Daten an |

### Rückgabewert

Die Zeichenkette, die die Base-64-kodierte Darstellung des Eingabearrays enthält

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) Methode


Base-64 codiert einen Bereich von Elementen im angegebenen Byte-Array und gibt die codierten Daten als Zeichenkette zurück.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Das Array von Bytes, das den zu kodierenden Elementbereich enthält |
| offset_in | int | Ein Index eines Elements im Eingabearray, an dem der zu kodierende Bereich beginnt |
| length | int | Die Länge des zu kodierenden Elementbereichs |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Gibt Formatierungsoptionen für die Base-64-kodierten Daten an |

### Rückgabewert

Die Zeichenkette, die die Base-64-kodierte Darstellung des gewünschten Bereichs des Eingabearrays enthält

## Siehe auch

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)