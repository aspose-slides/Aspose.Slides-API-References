---
title: Trim()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa wszystkie znaki białe z początku i końca ciągu.
type: docs
weight: 677
url: /pl/system/string/trim/
---
## String::Trim() const metoda

Usuwa wszystkie białe znaki z początku i końca ciągu.

```cpp
String System::String::Trim() const
```

### Wartość zwracana

[String](../) bez białych znaków na początku i końcu.

## String::Trim(char_t) const metoda

Usuwa wszystkie wystąpienia podanego znaku z początku i końca ciągu.

```cpp
String System::String::Trim(char_t ch) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ch | char_t | Symbol do usunięcia. |

### Wartość zwracana

Wynik usuwania.

## String::Trim(const String\&) const metoda

Usuwa wszystkie wystąpienia podanych znaków z początku i końca ciągu.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) znaków do usunięcia. |

### Wartość zwracana

[String](../) bez usuniętych znaków.

## String::Trim(const ArrayPtr\<char_t\>\&) const metoda

Usuwa wszystkie wystąpienia podanych znaków z początku i końca ciągu.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do usunięcia. |

### Wartość zwracana

[String](../) bez usuniętych znaków.

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)