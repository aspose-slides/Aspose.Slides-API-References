---
title: TrimEnd()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa wszystkie białe znaki z końca łańcucha.
type: docs
weight: 703
url: /pl/system/string/trimend/
---
## String::TrimEnd() const metoda

Usuwa wszystkie znaki białych znaków z końca łańcucha.

```cpp
String System::String::TrimEnd() const
```

### Wartość zwracana

[String](../) bez znaków białych na początku.

## String::TrimEnd(char_t) const metoda

Usuwa wszystkie wystąpienia podanego znaku z końca łańcucha.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ch | char_t | Symbol do usunięcia. |

### Wartość zwracana

Wynik usunięcia.

## String::TrimEnd(const String\&) const metoda

Usuwa wszystkie wystąpienia podanych znaków z końca łańcucha.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) znaków do usunięcia. |

### Wartość zwracana

[String](../) bez usuniętych znaków.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const metoda

Usuwa wszystkie wystąpienia podanych znaków z końca łańcucha.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
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