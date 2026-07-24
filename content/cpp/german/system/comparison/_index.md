---
title: Comparison
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Zeiger auf die Methode dar, die zwei Objekte desselben Typs vergleicht. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 183
url: /de/system/comparison/
---
## Vergleichsklasse

Stellt einen Zeiger auf die Methode dar, die zwei Objekte desselben Typs vergleicht. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Objekte, die die Methode vergleicht |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Ruft das aufrufbare Objekt auf, auf das das aktuelle Objekt verweist. |
## Hinweise

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Die Template-Klasse, die ein dynamisches Array repräsentiert.
template <typename T>
class MyArray
{
  // Wird verwendet, um die Array-Daten zu speichern.
  std::vector<T> m_data;

public:
  // Konstruiert eine neue Instanz unseres dynamischen Arrays.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Wird verwendet, um die Array-Daten zu sortieren. Diese Methode akzeptiert eine Instanz von dem
  // 'System::Comparison' Template-Klasse.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Gibt die Anzahl der Elemente zurück, die unser dynamisches Array speichert.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Wird verwendet, um ein Element am angegebenen Index zu erhalten.
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
  // Erstelle eine Instanz der MyArray-Klasse mit den angegebenen Elementen.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Sortiere nach aufsteigenden Elementen des dynamischen Arrays.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Gib die Elemente des dynamischen Arrays aus.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
a
b
c
d
e
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)