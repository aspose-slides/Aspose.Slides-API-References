---
title: Write()
second_title: Aspose.Slides für C++ API Referenz
description: Schreibt das angegebene Zeichen in den Stream.
type: docs
weight: 79
url: /de/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) Methode


Schreibt das angegebene Zeichen in den Stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Das zu schreibende Zeichen |

## StreamWriter::Write(const String\&) Methode


Schreibt die angegebene Zeichenkette in den Stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Die zu schreibende Zeichenkette |

## StreamWriter::Write(const SharedPtr\<Object\>\&) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts in den Stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Das zu schreibende Objekt |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) Methode


Schreibt alle Zeichen aus dem angegebenen Array in den Stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) Methode


Schreibt den angegebenen Teilbereich von UTF-16-Zeichen aus dem angegebenen Zeichenarray in den Stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |
| index | **int32_t** | Ein 0-basierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Zeichen im zu schreibenden Teilbereich; -1 gibt an, dass der Teilbereich am Ende des **buffer**-Arrays endet |

## StreamWriter::Write(const char_t *) Methode


Schreibt die angegebene C-Zeichenkette in den Stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const char_t * | Die zu schreibende C-Zeichenkette |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) Methode


Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts in den Stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Objekts |

### Argumente

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
* Library [Aspose.Slides](../../../)