---
title: TrimStart()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa wszystkie białe znaki z początku łańcucha.
type: docs
weight: 690
url: /pl/system/string/trimstart/
---
## String::TrimStart() const metoda

Usuwa wszystkie białe znaki z początku łańcucha.

```cpp
String System::String::TrimStart() const
```

### Wartość zwracana

[String](../) z brakiem białych znaków na początku.

## String::TrimStart(char_t) const metoda

Usuwa wszystkie wystąpienia przekazanego znaku z początku łańcucha.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ch | char_t | Symbol do usunięcia. |

### Wartość zwracana

Wynik usunięcia.

## String::TrimStart(const String\&) const metoda

Usuwa wszystkie wystąpienia przekazanych znaków z początku łańcucha.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) znaków do usunięcia. |

### Wartość zwracana

[String](../) bez usuniętych znaków.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const metoda

Usuwa wszystkie wystąpienia przekazanych znaków z początku łańcucha.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
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