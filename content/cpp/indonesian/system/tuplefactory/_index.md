---
title: TupleFactory
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode statis untuk membuat objek tuple.
type: docs
weight: 1366
url: /id/system/tuplefactory/
---
## TupleFactory kelas

Menyediakan metode statis untuk membuat objek tuple.

```cpp
class TupleFactory
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Membuat objek tuple baru. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Membuat 8-tuple baru. Elemen ke-8 disimpan di dalam [Tuple](../tuple/). |
## Catatan



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)