---
title: AreFPandArithmetic
second_title: Aspose.Slides для C++ справка API
description: Проверяет, что T1 является арифметическим, а T2 — типом с плавающей точкой, или наоборот. Если так, устанавливает значение члена в true, иначе — false.
type: docs
weight: 79
url: /ru/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

Проверяет, что **T1** является арифметическим, а **T2** — типом с плавающей точкой, или наоборот. Если так, устанавливает значение члена в true, иначе — false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## См. также

* Пр пространство имён [System::TestPredicates::TypeTraits](../)
* Библиотека [Aspose.Slides](../../)