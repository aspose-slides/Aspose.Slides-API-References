---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API リファレンス
description: Is-instance-ofは、IsInstanceOfアサーションの引数を比較します。
type: docs
weight: 118
url: /ja/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) 関数


Is-instance-ofは、IsInstanceOfアサーションの引数を比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 引数の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | **obj** の型と比較される型を表す typeInfo オブジェクト |
| obj | const T\& | 指定された型と比較する型を持つオブジェクト |

### 戻り値

gtest 形式のアサーション結果。

## 関連項目

* クラス [TypeInfo](../../system/typeinfo/)
* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)