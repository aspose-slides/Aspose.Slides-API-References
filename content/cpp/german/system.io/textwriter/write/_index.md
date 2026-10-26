---
title: Write()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts in den Stream.
type: docs
weight: 105
url: /de/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Das zu schreibende Objekt |

## TextWriter::Write(bool) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen booleschen Werts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | **bool** | Der zu schreibende Wert |

## TextWriter::Write(char_t) Methode


Schreibt das angegebene Zeichen in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | char_t | Der zu schreibende Wert |

## TextWriter::Write(Decimal) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen [Decimal](../../../system/decimal/)-Objekts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Das zu schreibende Objekt |

## TextWriter::Write(double) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen Gleitkommawerts mit doppelter Genauigkeit in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | **double** | Der zu schreibende Wert |

## TextWriter::Write(int) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen 32-Bit-Ganzzahlwerts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | int | Der zu schreibende Wert |

## TextWriter::Write(int64_t) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen 64-Bit-Ganzzahlwerts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | **int64_t** | Der zu schreibende Wert |

## TextWriter::Write(float) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen Gleitkommawerts mit einfacher Genauigkeit in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu schreibende Wert |

## TextWriter::Write(const String\&) Methode


Schreibt die angegebene Zeichenkette in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Die zu schreibende Zeichenkette |

## TextWriter::Write(uint32_t) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen vorzeichenlosen 32-Bit-Ganzzahlwerts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | **uint32_t** | Der zu schreibende Wert |

## TextWriter::Write(uint64_t) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen vorzeichenlosen 64-Bit-Ganzzahlwerts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | **uint64_t** | Der zu schreibende Wert |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) Methode


Schreibt alle Zeichen aus dem angegebenen Array in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) Methode


Schreibt den angegebenen Teilbereich von UTF-16-Zeichen aus dem angegebenen Zeichenarray in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |
| index | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Zeichen im zu schreibenden Teilbereich; -1 gibt an, dass der Teilbereich dort endet, wo das **buffer**-Array endet |

## TextWriter::Write(const char_t *) Methode


Schreibt die angegebene C-Zeichenkette in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die zu schreibende C-Zeichenkette |

## TextWriter::Write(const TypeInfo\&) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../../../system/typeinfo/)-Objekts in den Stream.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Das zu schreibende Objekt |

## TextWriter::Write(const String\&, const TArgs\&...) Methode


Schreibt die angegebenen Werte, formatiert gemäß dem angegebenen Format, in den Stream.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TArgs | Die Liste der Typen der zu schreibenden Werte |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Das Zeichenkettenformat |
| args | const TArgs\&... | Die zu schreibenden Werte |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TextWriter](../)
* Klasse [Decimal](../../../system/decimal/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)