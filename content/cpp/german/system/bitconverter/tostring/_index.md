---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert alle Werte des angegebenen Byte-Arrays in ihre hexadezimale Zeichenkettenrepräsentation. Der Fall der Buchstaben, die in der hexadezimalen Schreibweise verwendet werden, sowie das Trennzeichen, das zwischen benachbarten Bytes eingefügt wird, werden über die entsprechenden Argumente angegeben.
type: docs
weight: 157
url: /de/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) Methode


Konvertiert alle Werte des angegebenen Byte-Arrays in ihre hexadezimale Zeichenkettenrepräsentation. Der Fall der Buchstaben, die in der hexadezimalen Schreibweise verwendet werden, sowie das Trennzeichen, das zwischen benachbarten Bytes eingefügt wird, werden über die entsprechenden Argumente angegeben.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| uppercase | **bool** | Gibt den Fall der Buchstaben an, die in der resultierenden hexadezimalen Darstellung verwendet werden |
| separator | const [String](../../string/)\& | Eine Zeichenkette, die als Trennzeichen zwischen jedem Paar benachbarter Bytes in der resultierenden Zeichenkette eingefügt wird |

### Rückgabewert

[String](../../string/) enthält die hexadezimale Darstellung des angegebenen Byte-Arrays

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) Methode


Konvertiert Werte des angegebenen Byte-Arrays in ihre hexadezimale Zeichenkettenrepräsentation, beginnend an dem angegebenen Index.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im angegebenen Array, an dem mit dem Konvertieren begonnen werden soll |

### Rückgabewert

[String](../../string/) enthält die hexadezimale Darstellung des angegebenen Bereichs von Elementen des angegebenen Arrays

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) Methode


Konvertiert einen Wertebereich des angegebenen Byte-Arrays in seine hexadezimale Zeichenkettenrepräsentation.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im angegebenen Array, an dem der Bereich der zu konvertierenden Byte-Array-Elemente beginnt |
| length | int | Die Länge des Bereichs der zu konvertierenden Byte-Array-Elemente |

### Rückgabewert

[String](../../string/) enthält die hexadezimale Darstellung des angegebenen Bereichs von Elementen des angegebenen Arrays

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)