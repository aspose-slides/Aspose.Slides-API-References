---
title: AreBoxedValuesEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つの Boxed 型を等価比較します。
type: docs
weight: 79
url: /ja/system.testpredicates.details.sharedptrasserts/areboxedvaluesequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *, const char *, const SharedPtr\<BoxedValueBase\>\&, const SharedPtr\<BoxedValueBase\>\&) function


2つの Boxed 型を等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<BoxedValueBase> &lhs, const SharedPtr<BoxedValueBase> &rhs)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | LHS の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | RHS の値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [BoxedValueBase](../../system/boxedvaluebase/)
* 名前空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* ライブラリ [Aspose.Slides](../../)