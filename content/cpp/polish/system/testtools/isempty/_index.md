---
title: IsEmpty()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Sprawdza, czy ciąg jest pusty.
type: docs
weight: 14
url: /pl/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) metoda

Sprawdza, czy ciąg jest pusty.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) do sprawdzenia, czy jest pusty. |

### Wartość zwracana

true, jeśli ciąg jest pusty (null-length), false w przeciwnym razie.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) metoda

Sprawdza, czy kolekcja jest pusta.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Kolekcja do sprawdzenia. |

### Wartość zwracana

true, jeśli kolekcja ma zerową liczbę elementów, false w przeciwnym razie.

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Struktura [TestTools](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)