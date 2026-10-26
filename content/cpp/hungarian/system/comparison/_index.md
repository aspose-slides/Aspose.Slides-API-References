---
title: Comparison
second_title: Aspose.Slides C++ API referencia
description: "Egy mutatót képvisel a metódusra, amely összehasonlít két azonos típusú objektumot. Ezt a típust a stack-en kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ezen típusú objektumok kezelésére."
type: docs
weight: 183
url: /hu/system/comparison/
---
## Comparison osztály

Egy mutatót képvisel a metódusra, amely összehasonlít két, azonos típusú objektumot. Ezt a típust a stacken kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ezen típusú objektumok kezelésekor.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A metódus által összehasonlított objektumok típusa |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Meghívja a jelenlegi objektum által mutatott meghívható objektumot. |

## Megjegyzések



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

//  A sablonos osztály, amely egy dinamikus tömböt képvisel.
template <typename T>
class MyArray
{
  //  A tömb adatait tárolja.
  std::vector<T> m_data;

public:
  //  Létrehozza a mi dinamikus tömbünk új példányát.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  //  A tömb adatait rendezi. Ez a metódus egy példányt fogad a
  //  'System::Comparison' sablonos osztályt.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  //  Visszaadja a dinamikus tömbünk által tárolt elemek számát.
  size_t get_Size()
  {
    return m_data.size();
  }

  //  Egy elemet kér le a megadott indexnél.
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
  //  Létrehoz egy MyArray osztálypéldányt a megadott elemekkel.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  //  Rendezi a dinamikus tömb elemeit növekvő sorrendbe.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  //  Kiírja a dinamikus tömb elemeit.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet állítja elő:
a
b
c
d
e
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)