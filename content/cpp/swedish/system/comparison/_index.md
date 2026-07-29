---
title: Comparison
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en pekare till metoden som jämför två objekt av samma typ. Denna typ bör allokeras på stacken och skickas till funktioner med värde eller med referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ."
type: docs
weight: 183
url: /sv/system/comparison/
---
## Jämförelseklass

Representerar en pekare till metoden som jämför två objekt av samma typ. Denna typ bör allokeras på stacken och skickas till funktioner med värde eller med referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på objekten som metoden jämför |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Invokar det anropbara objektet som den aktuella objektet pekar på. |
## Anmärkningar



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Mallklassen som representerar en dynamisk array.
template <typename T>
class MyArray
{
  // Används för att lagra arrayens data.
  std::vector<T> m_data;

public:
  // Skapar en ny instans av vår dynamiska array.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Används för att sortera arrayens data. Denna metod accepterar en instans av
  // 'System::Comparison' mallklass.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Returnerar antalet element som vår dynamiska array lagrar.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Används för att hämta ett element på det angivna indexet.
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
  // Skapa en instans av MyArray-klassen med de angivna elementen.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Sortera efter stigande element i den dynamiska arrayen.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Skriv ut element i den dynamiska arrayen.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Det här kodexemplet producerar följande utskrift:
a
b
c
d
e
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)