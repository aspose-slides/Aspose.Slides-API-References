---
title: HolderInitializer
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Ta klasa służy do uzyskania trwałego odwołania do instancji obiektu, niezależnie od tego, czy jest to lvalue czy rvalue. Aby uzyskać takie odwołanie, użyj metody 'HoldIfTemporary', która ma trzy przeciążenia. Dwa z nich przyjmują rvalue jako parametr i po prostu zwracają odwołanie do niego. Trzecie, przeciwnie, przyjmuje lvalue jako parametr, tworzy kopię wskaźnika, a następnie zwraca odwołanie do tej kopii. Klasa posiada również metodę 'Hold', aby niewarunkowo utrzymać przekazaną wartość (używaną do kopiowania wartości lokalnych zmiennych na stosie lub ich referencji potomnych).
type: docs
weight: 1639
url: /pl/system/holderinitializer/
---
## HolderInitializer struct

Ta klasa służy do uzyskania trwałego odwołania do instancji obiektu, niezależnie od tego, czy jest to lvalue czy rvalue. Aby uzyskać takie odwołanie, użyj metody 'HoldIfTemporary', która posiada trzy przeciążenia. Dwa z nich przyjmują rvalue jako parametr i po prostu zwracają odwołanie do niego. Trzecie, przeciwnie, przyjmuje lvalue jako parametr, tworzy kopię wskaźnika, a następnie zwraca odwołanie do tej kopii. Klasa posiada również metodę 'Hold', aby niewarunkowo utrzymać przekazaną wartość (używaną do kopiowania wartości lokalnych zmiennych na stosie lub ich referencji potomnych).

```cpp
template<typename T,bool>class HolderInitializer
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu, który ma być przechowywany. |
| R | true, jeśli T jest typem referencyjnym (specjalizacja [SmartPtr](../smartptr/) lub typ [System::String](../string/)) i wymagana jest rzeczywista obsługa tymczasowych referencji, false – w przeciwnym razie. |

## Metody

| Metoda | Opis |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Kopiuje przekazane lvalue do holdera, a następnie zwraca odwołanie do holdera. Wywołujący powinien używać tej metody, aby niewarunkowo utrzymać przekazaną wartość. |
| [HolderInitializer](./holderinitializer/)(T\&) | Inicjalizuje odwołanie holdera przekazanym odwołaniem. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Zwraca odwołanie do rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Zwraca odwołanie do rvalue (non-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Kopiuje przekazane lvalue do holdera, a następnie zwraca odwołanie do holdera. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)