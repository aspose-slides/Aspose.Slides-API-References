---
title: AreFPandArithmetic
second_title: Aspose.Slides untuk Referensi API C++
description: Memeriksa bahwa T1 bersifat aritmetika dan T2 merupakan floating point, atau sebaliknya. Jika demikian, mengatur anggota value menjadi true, jika tidak maka false.
type: docs
weight: 79
url: /id/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Memeriksa bahwa **T1** bersifat aritmetika dan **T2** merupakan floating point, atau sebaliknya. Jika demikian, mengatur anggota value menjadi true, jika tidak maka false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Lihat Juga

* Ruang Nama [System::TestPredicates::TypeTraits](../)
* Perpustakaan [Aspose.Slides](../../)