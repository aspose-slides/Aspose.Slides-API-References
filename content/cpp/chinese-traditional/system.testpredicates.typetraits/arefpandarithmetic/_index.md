---
title: AreFPandArithmetic
second_title: Aspose.Slides for C++ API 參考
description: 檢查 T1 是否為算術型且 T2 為浮點型，或相反。如果是，則將 value 成員設為 true，否則為 false。
type: docs
weight: 79
url: /zh-hant/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

檢查 **T1** 是否為算術型且 **T2** 為浮點型，或反之。如果是，則將 value 成員設為 true，否則為 false。

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## 另請參閱

* 命名空間 [System::TestPredicates::TypeTraits](../)
* 函式庫 [Aspose.Slides](../../)