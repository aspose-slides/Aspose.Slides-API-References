---
title: Func
second_title: Aspose.Slides için C++ API Referansı
description: "Fonksiyon delege. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referans olarak geçirilmelidir. Bu tip nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 859
url: /tr/system/func/
---
## Func sınıf

Fonksiyon delege. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referans olarak geçirilmelidir. Bu tip nesneleri yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Args | Çağrı argümanları, ardından zorunlu dönüş tipi. |

## Metodlar

| Metod | Açıklama |
| --- | --- |
|  [Func](./func/)() | null-Func oluşturan varsayılan yapıcı. |
|  [Func](./func/)(T\&&) | [Func](./) nesnesini oluşturan ve ona değer (gerçek geri çağırma veya nullptr) atayan yapıcı. |
|  [Func](./func/)(const [Func](./)\&) | Kopya yapıcı. |
|  [Func](./func/)([Func](./)\&&) | Taşıma yapıcı. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Kopya atama. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Taşıma atama. |
|  [~Func](./~func/)() | Yıkıcı. |

## Açıklamalar

```cpp
#include "system/func.h"
#include <iostream"

// Bu işlev, System::Func delege örneğini bir parametre olarak kabul eder.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // System::Func delege örneği oluştur.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Oluşturulan örneği bir işlev argümanı olarak geçir.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
1
4
9
*/
```

## Ayrıca bakınız

* İsim alanı [System](../)
* Kütüphane [Aspose.Slides](../../)