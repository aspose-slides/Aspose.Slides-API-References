---
title: Insert()
second_title: Aspose.Slides pro C++ API Reference
description: Vkládá řetězec do pevné pozice builderu.
type: docs
weight: 183
url: /cs/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) metoda

Vkládá řetězec do pevné pozice builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) to insert. |

### Návratová hodnota

Tento ukazatel.

## StringBuilder::Insert(int32_t, const String\&, int32_t) metoda

Vkládá opakovaný řetězec do pevné pozice builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Position to insert characters into. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) to insert. |
| count | **int32_t** | How many times to repeat **value** string. |

### Návratová hodnota

Tento ukazatel.

## StringBuilder::Insert(int, char_t) metoda

Vkládá znak do pevné pozice builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| ch | char_t | Character to insert. |

### Návratová hodnota

Tento ukazatel.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) metoda

Vkládá znaky do pevné pozice builderu.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Position to insert characters into. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) to insert slice from. |
| startIndex | int | [Array](../../../system/array/) slice beginning index. |
| charCount | int | [Array](../../../system/array/) slice length. |

### Návratová hodnota

Tento ukazatel.

## StringBuilder::Insert(int, T) metoda

Vkládá hodnotu do pevné pozice builderu.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Parameter | type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| value | T | Value to format and insert. |

### Návratová hodnota

Tento ukazatel.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [StringBuilder](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Text](../../)
* Library [Aspose.Slides](../../../)