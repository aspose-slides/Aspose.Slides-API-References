---
title: Comparison
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een pointer voor naar de methode die twee objecten van hetzelfde type vergelijkt. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 183
url: /nl/system/comparison/
---
## Vergelijkingsklasse


Stelt een pointer voor naar de methode die twee objecten van hetzelfde type vergelijkt. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de objecten die de methode vergelijkt |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Roept het aanroepbare object aan waar het huidige object naar wijst. |
## Opmerkingen



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// De sjabloonklasse die een dynamische array vertegenwoordigt.
template <typename T>
class MyArray
{
  // Gebruikt om de arraygegevens op te slaan.
  std::vector<T> m_data;

public:
  // Construeert een nieuw exemplaar van onze dynamische array.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Gebruikt om de arraygegevens te sorteren. Deze methode accepteert een exemplaar van de
  // 'System::Comparison' sjabloonklasse.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Retourneert het aantal elementen dat onze dynamische array bevat.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Gebruikt om een element op de opgegeven index te krijgen.
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
  // Maak een exemplaar van de MyArray-klasse met de opgegeven elementen.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Sorteer op oplopende elementen van de dynamische array.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Print de elementen van de dynamische array.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
a
b
c
d
e
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)