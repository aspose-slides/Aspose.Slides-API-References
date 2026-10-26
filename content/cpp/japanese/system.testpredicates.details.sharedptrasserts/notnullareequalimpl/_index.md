---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列またはリストを等価比較します。
type: docs
weight: 40
url: /ja/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

配列またはリストを等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺コンテナ型。 |
| T2 | 右辺コンテナ型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T1\& | 左辺の値。 |
| rhs | const T2\& | 右辺の値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータ; パラメータの値は無視されます |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

IEnumerable インスタンスを等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺要素型。 |
| T2 | 右辺要素型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T1\& | 左辺の値。 |
| rhs | const T2\& | 右辺の値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータ; パラメータの値は無視されます |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) 関数

Equals メソッドを使用して未知の型を等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺オブジェクト型。 |
| T2 | 右辺オブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T1\& | 左辺の値。 |
| rhs | const T2\& | 右辺の値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)