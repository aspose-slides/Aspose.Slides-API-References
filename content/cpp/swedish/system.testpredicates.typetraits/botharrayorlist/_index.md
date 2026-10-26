---
title: BothArrayOrList
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om båda typargumenten är arrayer eller listor. Om så är fallet sätts value-medlemmen till true, annars sätts den till false.
type: docs
weight: 131
url: /sv/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Kontrollerar om båda typargumenten är arrayer eller listor. Om så är fallet sätts value-medlemmen till true, annars sätts den till false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Se också

* Namnrymd [System::TestPredicates::TypeTraits](../)
* Bibliotek [Aspose.Slides](../../)