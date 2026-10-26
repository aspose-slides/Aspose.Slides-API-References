---
title: WriteLine()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt Zeilenabschlusszeichen in den Stream.
type: docs
weight: 92
url: /de/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() Methode

Schreibt Zeilenabschlusszeichen in den Stream.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) Methode

Schreibt die angegebene Zeichenfolge, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Die zu schreibende Zeichenfolge |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Das zu schreibende Objekt |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) Methode

Schreibt alle Zeichen aus dem angegebenen Array, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von UTF-16-Zeichen aus dem angegebenen Zeichenarray, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |
| index | **int32_t** | Ein 0-basierter Index des Elements im **buffer**, ab dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Zeichen im zu schreibenden Teilbereich; -1 gibt an, dass der Teilbereich dort endet, wo das **buffer**-Array endet |

## StreamWriter::WriteLine(const char_t *) Methode

Schreibt die angegebene C-Zeichenkette, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const char_t * | Die zu schreibende C-Zeichenkette |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) Methode

Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Objekts |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Das zu schreibende Objekt |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StreamWriter](../)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)