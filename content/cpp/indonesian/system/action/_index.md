---
title: Action
second_title: Referensi API Aspose.Slides untuk C++
description: Tipe delegasi yang merujuk pada metode yang tidak mengembalikan nilai.
type: docs
weight: 3602
url: /id/system/action/
---
## Action typedef

Tipe delegasi yang merujuk pada metode yang tidak mengembalikan nilai.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Catatan

```cpp
#include <system/action.h>

using namespace System;

// Fungsi yang mencetak string yang diberikan.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Buat sebuah instance Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Panggil action.
  action(u"Hello, world!");

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Halo, dunia!
*/
```

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)