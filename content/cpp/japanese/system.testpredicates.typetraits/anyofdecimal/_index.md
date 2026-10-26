---
title: AnyOfDecimal
second_title: Aspose.Slides for C++ API リファレンス
description: "型引数の少なくとも1つが System::Decimal であることを確認します。そうであれば value メンバーを true に設定し、そうでなければ false です。"
type: docs
weight: 92
url: /ja/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

型引数の少なくとも1つが [System::Decimal](../../system/decimal/) であることをチェックします。そうであれば value メンバーを true に設定し、そうでなければ false です。

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)