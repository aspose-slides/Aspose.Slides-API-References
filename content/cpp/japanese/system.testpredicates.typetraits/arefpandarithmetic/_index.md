---
title: AreFPandArithmetic
second_title: Aspose.Slides for C++ API リファレンス
description: T1 が算術型で T2 が浮動小数点型であるか、またはその逆であるかを確認します。該当する場合は value メンバーを true に設定し、そうでない場合は false にします。
type: docs
weight: 79
url: /ja/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


**T1** が算術型で **T2** が浮動小数点型であるか、またはその逆であるかを確認します。該当する場合は value メンバーを true に設定し、そうでない場合は false にします。

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)