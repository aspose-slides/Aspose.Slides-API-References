---
title: WriteLine()
second_title: Aspose.Slides für C++ API Referenz
description: Schreibt Zeilenabschlusszeichen in den Stream.
type: docs
weight: 118
url: /de/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() Methode

Schreibt Zeilenabschlusszeichen in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Das zu schreibende Objekt |

## TextWriter::WriteLine(bool) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen booleschen Wertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **bool** | Der zu schreibende Wert |

## TextWriter::WriteLine(char_t) Methode

Schreibt das angegebene Zeichen, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Der zu schreibende Wert |

## TextWriter::WriteLine(Decimal) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen [Decimal](../../../system/decimal/)-Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Das zu schreibende Objekt |

## TextWriter::WriteLine(double) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen double-Genauigkeits-Gleitkommawertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Der zu schreibende Wert |

## TextWriter::WriteLine(int) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen 32-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | Der zu schreibende Wert |

## TextWriter::WriteLine(int64_t) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen 64-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **int64_t** | Der zu schreibende Wert |

## TextWriter::WriteLine(float) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen single-Precision-Gleitkommawertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu schreibende Wert |

## TextWriter::WriteLine(const String\&) Methode

Schreibt die angegebene Zeichenkette, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Die zu schreibende Zeichenkette |

## TextWriter::WriteLine(uint32_t) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen unsigned 32-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint32_t** | Der zu schreibende Wert |

## TextWriter::WriteLine(uint64_t) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen unsigned 64-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint64_t** | Der zu schreibende Wert |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) Methode

Schreibt alle Zeichen aus dem angegebenen Array, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von UTF-16-Zeichen aus dem angegebenen Zeichen-Array, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |
| index | **int32_t** | Ein 0-basierter Index des Elements in **buffer**, bei dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der im Teilbereich zu schreibenden Zeichen; -1 gibt an, dass der Teilbereich endet, wo das **buffer**-Array endet |

## TextWriter::WriteLine(const char_t *) Methode

Schreibt die angegebene C-Zeichenkette, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die zu schreibende C-Zeichenkette |

## TextWriter::WriteLine(const TypeInfo\&) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../../../system/typeinfo/)-Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Das zu schreibende Objekt |

## TextWriter::WriteLine(const String\&, const TArgs\&...) Methode

Schreibt die angegebenen Werte, formatiert gemäß dem angegebenen Format, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TArgs | Die Liste der Typen der zu schreibenden Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Das Zeichenketten-Format |
| args | const TArgs\&... | Die zu schreibenden Werte |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Class [Object](../../../system/object/)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)