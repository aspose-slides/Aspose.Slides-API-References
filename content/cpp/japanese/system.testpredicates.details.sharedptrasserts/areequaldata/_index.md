---
title: AreEqualData()
second_title: Aspose.Slides for C++ API リファレンス
description: "要素に対して System::Object::Equals を使用して 2 つのコンテナを等価比較します。SmartPtr 要素で動作します。"
type: docs
weight: 14
url: /ja/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) 関数

要素上で [System::Object::Equals](../../system/object/equals/) を使用して 2 つのコンテナを等価比較します。[SmartPtr](../../system/smartptr/) 要素で動作します。

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### テンプレートパラメータ

| Parameter | Description |
| --- | --- |
| T1 | LHS コンテナ型。 |
| T2 | RHS コンテナ型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS コンテナ参照。 |
| rhs | const T2\& | RHS コンテナ参照。 |

### 戻り値

含まれる要素とサイズが一致すれば true、そうでなければ false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) 関数

要素上で operator == を使用して 2 つのコンテナを等価比較します。SmartPtr でない要素で動作します。

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### テンプレートパラメータ

| Parameter | Description |
| --- | --- |
| T1 | LHS コンテナ型。 |
| T2 | RHS コンテナ型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS コンテナ。 |
| rhs | const T2\& | RHS コンテナ。 |

### 戻り値

含まれる要素とサイズが一致すれば true、そうでなければ false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) 関数

同一型の 2 つのコンテナを等価比較します。SmartPtr でない要素で動作します。

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### テンプレートパラメータ

| Parameter | Description |
| --- | --- |
| T1 | LHS コンテナ型。 |
| T2 | RHS コンテナ型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T\& | LHS コンテナ。 |
| rhs | const T\& | RHS コンテナ。 |

### 戻り値

含まれる要素とサイズが一致すれば true、そうでなければ false。

## 参照

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)