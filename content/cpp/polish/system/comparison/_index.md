---
title: Comparison
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Reprezentuje wskaźnik do metody, która porównuje dwa obiekty tego samego typu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 183
url: /pl/system/comparison/
---
## Klasa Comparison

Reprezentuje wskaźnik do metody, która porównuje dwa obiekty tego samego typu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj [System::SmartPtr](../smartptr/) klasy do zarządzania obiektami tego typu.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektów, które metoda porównuje |

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Wywołuje obiekt wywoływalny wskazywany przez bieżący obiekt. |

## Uwagi

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Szablon klasy reprezentujący dynamiczną tablicę.
template <typename T>
class MyArray
{
  // Używana do przechowywania danych tablicy.
  std::vector<T> m_data;

public:
  // Tworzy nową instancję naszej dynamicznej tablicy.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Używana do sortowania danych tablicy. Ta metoda przyjmuje instancję
  // 'System::Comparison' klasy szablonu.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Zwraca liczbę elementów, które przechowuje nasza dynamiczna tablica.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Używana do pobrania elementu pod określonym indeksem.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // Utwórz instancję klasy MyArray z określonymi elementami.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Sortuj rosnąco elementy dynamicznej tablicy.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Wypisz elementy dynamicznej tablicy.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
a
b
c
d
e
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)