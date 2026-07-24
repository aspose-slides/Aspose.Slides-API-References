---
title: Write()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeichenkettenrepräsentation des angegebenen Objekts im Standardausgabestream aus.
type: docs
weight: 1
url: /de/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) Methode

Gibt die Zeichenkettenrepräsentation des angegebenen Objekts im Standardausgabestream aus.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des auszugebenden Objekts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) auszugeben |

## Console::Write(bool) Methode

Gibt die Zeichenkettenrepräsentation des booleschen Wertes im Standardausgabestream aus.

```cpp
static void System::Console::Write(bool value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **bool** | Der auszugebende Wert |

## Console::Write(char_t) Methode

Gibt den angegebenen Zeichenwert im Standardausgabestream aus.

```cpp
static void System::Console::Write(char_t value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Der auszugebende Wert |

## Console::Write(const ArrayPtr\<char_t\>\&) Methode

Gibt die Zeichenkettenrepräsentation des angegebenen Zeichen-Arrays im Standardausgabestream aus.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Das auszugebende Array |

## Console::Write(const Decimal\&) Methode

Gibt die Zeichenkettenrepräsentation des [Decimal](../../decimal/)-Wertes im Standardausgabestream aus.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Der auszugebende Wert |

## Console::Write(double) Methode

Gibt die Zeichenkettenrepräsentation des double-genauen Gleitkommawerts im Standardausgabestream aus.

```cpp
static void System::Console::Write(double value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Der auszugebende Wert |

## Console::Write(float) Methode

Gibt die Zeichenkettenrepräsentation des single-genauen Gleitkommawerts im Standardausgabestream aus.

```cpp
static void System::Console::Write(float value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der auszugebende Wert |

## Console::Write(int32_t) Methode

Gibt die Zeichenkettenrepräsentation des 32-Bit-Ganzzahlwerts im Standardausgabestream aus.

```cpp
static void System::Console::Write(int32_t value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **int32_t** | Der auszugebende Wert |

## Console::Write(int64_t) Methode

Gibt die Zeichenkettenrepräsentation des 64-Bit-Ganzzahlwerts im Standardausgabestream aus.

```cpp
static void System::Console::Write(int64_t value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **int64_t** | Der auszugebende Wert |

## Console::Write(const String\&) Methode

Gibt das angegebene Zeichenkettenobjekt im Standardausgabestream aus.

```cpp
static void System::Console::Write(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Das auszugebende Zeichenkettenobjekt |

## Console::Write(const char_t *) Methode

Gibt die angegebene C-Zeichenkette im Standardausgabestream aus.

```cpp
static void System::Console::Write(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Das auszugebende C-String |

## Console::Write(const TypeInfo\&) Methode

Gibt die Zeichenkettenrepräsentation des [TypeInfo](../../typeinfo/)-Wertes im Standardausgabestream aus.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Der auszugebende Wert |

## Console::Write(uint32_t) Methode

Gibt die Zeichenkettenrepräsentation des vorzeichenlosen 32-Bit-Ganzzahlwerts im Standardausgabestream aus.

```cpp
static void System::Console::Write(uint32_t value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint32_t** | Der auszugebende Wert |

## Console::Write(uint64_t) Methode

Gibt die Zeichenkettenrepräsentation des vorzeichenlosen 64-Bit-Ganzzahlwerts im Standardausgabestream aus.

```cpp
static void System::Console::Write(uint64_t value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint64_t** | Der auszugebende Wert |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) Methode

Gibt die Zeichenkettenrepräsentation des angegebenen Bereichs des angegebenen Zeichen-Arrays im Standardausgabestream aus.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Das Zeichen-Array |
| index | **int32_t** | Der Index im Array, an dem der auszugebende Bereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im auszugebenden Bereich |

## Console::Write(const String\&, Args\&&...) Methode

Gibt die Zeichenkettenrepräsentation der angegebenen Argumente, formatiert gemäß dem angegebenen Format, im Standardausgabestream aus.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| The | Typen der auszugebenden Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../string/)\& | Das Zeichenkettenformat |
| args | Args\&&... | Die auszugebenden Werte |

## Console::Write(const char *) Methode




```cpp
static void System::Console::Write(const char *)=delete
```

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)