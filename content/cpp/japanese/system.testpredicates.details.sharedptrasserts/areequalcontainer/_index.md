---
title: AreEqualContainer()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素に対して operator == を使用して 2 つのコンテナを等価比較します。SmartPtr でない要素で動作します。
type: docs
weight: 1
url: /ja/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

要素に対して operator == を使用して 2 つのコンテナを等価比較します。SmartPtr でない要素で動作します。

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS コンテナ型。 |
| T2 | RHS コンテナ型。 |

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs | const T1\& | LHS コンテナ。 |
| rhs | const T2\& | RHS コンテナ。 |

### Return Value

含まれる要素とサイズが一致すれば true、そうでなければ false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

要素に対して [System::Object::Equals](../../system/object/equals/) を使用して 2 つのコンテナを等価比較します。[SmartPtr](../../system/smartptr/) 要素で動作します。

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS コンテナ型。 |
| T2 | RHS コンテナ型。 |

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs | const T1\& | LHS コンテナ参照。 |
| rhs | const T2\& | RHS コンテナ参照。 |

### Return Value

含まれる要素とサイズが一致すれば true、そうでなければ false。

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)