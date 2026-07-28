---
title: IsNullOrEmpty()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Sprawdza, czy kolekcja jest null lub pusta.
type: docs
weight: 27
url: /pl/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) metoda

Sprawdza, czy kolekcja jest pusta lub ma wartość null.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
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

Zwraca true, jeśli kolekcja jest null lub ma zerową liczbę elementów, w przeciwnym razie false.

## TestTools::IsNullOrEmpty(const System::String\&) metoda

Sprawdza, czy ciąg znaków jest null lub pusty.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) do sprawdzenia. |

### Wartość zwracana

Zwraca true, jeśli ciąg znaków jest null lub ma zerową długość, w przeciwnym razie false.

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Struktura [TestTools](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)