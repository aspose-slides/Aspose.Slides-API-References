---
title: Comparison
second_title: Aspose.Slides pro C++ API Reference
description: "Representuje ukazatel na metodu, která porovnává dva objekty stejného typu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 183
url: /cs/system/comparison/
---
## Comparison třída

Representuje ukazatel na metodu, která porovnává dva objekty stejného typu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k řízení objektů tohoto typu.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektů, které metoda porovnává |

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Vyvolá volatelný objekt, na který ukazuje aktuální objekt. |

## Poznámky

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Šablonová třída, která představuje dynamické pole.
template <typename T>
class MyArray
{
  // Používá se k uložení dat pole.
  std::vector<T> m_data;

public:
  // Vytvoří novou instanci našeho dynamického pole.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Používá se k řazení dat pole. Tato metoda přijímá instanci
  // 'System::Comparison' šablonové třídy.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Vrací počet prvků, které naše dynamické pole ukládá.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Používá se k získání prvku na zadaném indexu.
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
  // Vytvořte instanci třídy MyArray se zadanými prvky.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Seřaďte podle vzestupných prvků dynamického pole.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Vytiskněte prvky dynamického pole.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
a
b
c
d
e
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)