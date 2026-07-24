---
title: Comparison
second_title: Aspose.Slides için C++ API Referansı
description: "Aynı tipte iki nesneyi karşılaştıran yönteme bir işaretçi temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer veya referans olarak geçirilmelidir. Bu tip nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 183
url: /tr/system/comparison/
---
## Karşılaştırma sınıfı

Aynı tipte iki nesneyi karşılaştıran yönteme bir işaretçi temsil eder. Bu tip stack üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. [System::SmartPtr](../smartptr/) sınıfını bu tip nesneleri yönetmek için asla kullanmayın.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yöntemin karşılaştırdığı nesnelerin tipi |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Geçerli nesnenin işaret ettiği çağrılabilir nesneyi yürütür. |
## Açıklamalar



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Dinamik bir diziyi temsil eden şablon sınıfı.
template <typename T>
class MyArray
{
  // Dizinin verilerini saklamak için kullanılır.
  std::vector<T> m_data;

public:
  // Dinamik dizimizin yeni bir örneğini oluşturur.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Dizinin verilerini sıralamak için kullanılır. Bu yöntem bir örnek alır
  // 'System::Comparison' şablon sınıfı.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Dinamik dizimizin sakladığı öğe sayısını döndürür.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Belirtilen indeksteki öğeyi almak için kullanılır.
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
  // Belirtilen öğelerle MyArray sınıfının bir örneğini oluşturur.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Dinamik dizinin artan öğeleriyle sıralar.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Dinamik dizinin öğelerini yazdırır.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
a
b
c
d
e
*/
```

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)