---
title: Boolean
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas yang menyimpan anggota statis dari tipe System.Boolean .Net.
type: docs
weight: 79
url: /id/system/boolean/
---
## Kelas Boolean

Kelas yang menyimpan anggota statis dari tipe [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Mengonversi string yang ditentukan menjadi nilai tipe bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Mengonversi string yang ditentukan menjadi nilai tipe bool. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representasi nilai boolean 'false'. |
| static [TrueString](./truestring/) | [String](../string/) representasi nilai boolean 'true'. |

## Catatan



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Buat variabel boolean.
  bool isWeekend = false;

  // Urai string masukan dan cetak hasil.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Is weekend: Yes
*/
```

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)