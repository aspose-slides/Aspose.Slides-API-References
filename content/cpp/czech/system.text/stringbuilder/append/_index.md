---
title: Append()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá znak do builderu.
type: docs
weight: 118
url: /cs/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metoda


Přidá znak do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Hodnota znaku. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(char_t, int) metoda


Přidá znaky do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Hodnota znaku. |
| count | int | Kolikrát se má vložený znak opakovat. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) metoda


Přidá pole znaků do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Znaky k přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metoda


Přidá část pole znaků do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Znaky k přidání. |
| startIndex | int | Počáteční index řezu. |
| charCount | int | Délka řezu. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(const String\&) metoda


Přidá řetězec do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) k přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(const String\&, int, int) metoda


Přidá část řetězce do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) k přidání. |
| startIndex | int | Počáteční index řezu. |
| charCount | int | Délka řezu. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(const SharedPtr\<T\>\&) metoda


Přidá řetězcovou reprezentaci objektu do builderu.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) k serializaci a přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metoda


Přidá obsah builderu do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder, ze kterého se přidá obsah. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(float) metoda


Přidá hodnotu s plovoucí desetinnou čárkou do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| f | **float** | Hodnota k serializaci a přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(double) metoda


Přidá hodnotu s plovoucí desetinnou čárkou do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| df | **double** | Hodnota k serializaci a přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(int) metoda


Přidá celočíselnou hodnotu do builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | int | Hodnota k serializaci a přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(T) metoda


Přidá aritmetickou hodnotu do builderu.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Aritmetický typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T | Hodnota k serializaci a přidání. |

### Návratová hodnota

This pointer.

## StringBuilder::Append(E) metoda


Přidá řetězcovou reprezentaci hodnoty výčtu do builderu.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| E | [Enum](../../../system/enum/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| e | E | Hodnota k serializaci a přidání. |

### Návratová hodnota

This pointer.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)