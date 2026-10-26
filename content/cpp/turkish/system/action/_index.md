---
title: Action
second_title: Aspose.Slides için C++ API Referansı
description: Geri dönüş değeri olmayan metodları referans alan delege türü.
type: docs
weight: 3602
url: /tr/system/action/
---
## Action typedef


Geri dönüş değeri olmayan metodları referans alan delege türü.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Açıklamalar



```cpp
#include <system/action.h>

using namespace System;

// Geçilen dizgiyi yazdıran fonksiyon.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Action’ın bir örneğini oluştur.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Action’ı çağır.
  action(u"Hello, world!");

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Merhaba, dünya!
*/
```

## İlgili

* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)