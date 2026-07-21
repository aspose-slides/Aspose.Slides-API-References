---
title: AnyOfDecimal
second_title: Aspose.Slides для C++ справочник API
description: "Проверяет, что хотя бы один из аргументов типа является System::Decimal. Если да, устанавливает член value в true, в противном случае — false."
type: docs
weight: 92
url: /ru/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Проверяет, что хотя бы один из аргументов типа является [System::Decimal](../../system/decimal/). Если да, устанавливает член value в true, в противном случае — false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## См. также

* Простоймя имён [System::TestPredicates::TypeTraits](../)
* Библиотека [Aspose.Slides](../../)