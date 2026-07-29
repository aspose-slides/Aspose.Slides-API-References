---
title: AnyOfDecimal
second_title: Aspose.Slides för C++ API-referens
description: "Kontrollerar att minst ett av typargumenten är System::Decimal. Om så är fallet sätter värdemedlemmen till true, annars är den false."
type: docs
weight: 92
url: /sv/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Kontrollerar att minst ett av typargumenten är [System::Decimal](../../system/decimal/). Om så är fallet sätter värdemedlemmen till true, annars är den false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## Se även

* Namnrymd [System::TestPredicates::TypeTraits](../)
* Bibliotek [Aspose.Slides](../../)