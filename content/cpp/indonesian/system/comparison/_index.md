---
title: Comparison
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pointer ke metode yang membandingkan dua objek dengan tipe yang sama. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi sebagai nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek dari tipe ini."
type: docs
weight: 183
url: /id/system/comparison/
---
## Comparison kelas

Mewakili pointer ke metode yang membandingkan dua objek dengan tipe yang sama. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi sebagai nilai atau referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek dari tipe ini.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe objek yang dibandingkan oleh metode |
## Metode

| Method | Description |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Memanggil objek yang dapat dipanggil yang ditunjuk oleh objek saat ini. |
## Catatan



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Kelas templat yang mewakili array dinamis.
template <typename T>
class MyArray
{
  // Digunakan untuk menyimpan data array.
  std::vector<T> m_data;

public:
  // Membuat instance baru dari array dinamis kami.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Digunakan untuk mengurutkan data array.
  // kelas templat 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Mengembalikan jumlah elemen yang disimpan oleh array dinamis kami.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Digunakan untuk mendapatkan elemen pada indeks yang ditentukan.
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
  // Membuat instance kelas MyArray dengan elemen yang ditentukan.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Urutkan secara naik elemen array dinamis.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Cetak elemen array dinamis.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
a
b
c
d
e
*/
```

## Lihat Juga

* Ruang nama [System](../)
* Library [Aspose.Slides](../../)