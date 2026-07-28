---
title: TryParse()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Próbuje przekonwertować podany ciąg znaków na równoważną stałą wyliczeniową.
type: docs
weight: 79
url: /pl/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metoda

Próbuje przekonwertować podany ciąg znaków na równoważną stałą wyliczeniową.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) interpretowany jako zawierający nazwę stałej wyliczeniowej |
| result | E\& | Parametr wyjściowy, który w przypadku pomyślnej konwersji zawiera wynik konwersji zwracany przez funkcję |

### Wartość zwracana

True jeśli konwersja się powiodła, w przeciwnym razie - false

## Enum::TryParse(const String\&, bool, E\&) metoda

Próbuje przekonwertować podany ciąg znaków na równoważną stałą wyliczeniową.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) interpretowany jako zawierający nazwę stałej wyliczeniowej |
| ignoreCase | **bool** | Określa, czy wielkość liter ma być ignorowana przy interpretacji ciągu |
| result | E\& | Parametr wyjściowy, który w przypadku pomyślnej konwersji zawiera wynik konwersji zwracany przy powrocie funkcji |

### Wartość zwracana

True jeśli konwersja się powiodła, w przeciwnym razie - false

## Zobacz także

* Klasa [String](../../string/)
* Struktura [Enum](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)