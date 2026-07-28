---
title: Insert()
second_title: Referencja API Aspose.Slides dla C++
description: Wstawia ciąg znaków w stałą pozycję buildera.
type: docs
weight: 183
url: /pl/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) metoda

Wstawia ciąg znaków w stałą pozycję buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Pozycja, w której wstawia się znaki. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) do wstawienia. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Insert(int32_t, const String\&, int32_t) metoda

Wstawia powtarzany ciąg znaków w stałą pozycję buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja, w której wstawia się znaki. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) do wstawienia. |
| count | **int32_t** | Ile razy powtórzyć ciąg **value**. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Insert(int, char_t) metoda

Wstawia znak w stałą pozycję buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Pozycja, w której wstawia się znaki. |
| ch | char_t | Znak do wstawienia. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) metoda

Wstawia znaki w stałą pozycję buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja, w której wstawia się znaki. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) do wstawienia wycinka z. |
| startIndex | int | [Array](../../../system/array/) indeks początku wycinka. |
| charCount | int | [Array](../../../system/array/) długość wycinka. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Insert(int, T) metoda

Wstawia wartość w stałą pozycję buildera.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Parametr | typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Pozycja, w której wstawia się znaki. |
| value | T | Wartość do sformatowania i wstawienia. |

### Wartość zwracana

Ten wskaźnik.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [StringBuilder](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)