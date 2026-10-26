---
title: Predicate
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili pointer ke predikat - entitas yang dapat dipanggil yang menerima satu argumen dan mengembalikan nilai bool.
type: docs
weight: 4187
url: /id/system/predicate/
---
## Typedef Predikat

Mewakili pointer ke predikat - entitas yang dapat dipanggil yang menerima satu argumen dan mengembalikan nilai bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Catatan



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Isi array.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Buat predikat yang mengembalikan elemen array yang lebih besar dari 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Temukan elemen pertama dari array menggunakan predikat yang dibuat dan cetak.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
5
*/
```

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)