---
title: AreEqualContainer()
second_title: Aspose.Slides for C++ API 參考
description: 使用 operator == 對元素進行等值比較。適用於非 SmartPtr 元素。
type: docs
weight: 1
url: /zh-hant/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

使用 operator == 對元素進行相等比較，適用於非 SmartPtr 元素。

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | LHS 容器類型。 |
| T2 | RHS 容器類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs | const T1\& | LHS 容器。 |
| rhs | const T2\& | RHS 容器。 |

### 返回值

如果包含的元素和大小相符則返回 true，否則返回 false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

使用 [System::Object::Equals](../../system/object/equals/) 對元素進行相等比較，適用於 [SmartPtr](../../system/smartptr/) 元素。

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | LHS 容器類型。 |
| T2 | RHS 容器類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs | const T1\& | LHS 容器參照。 |
| rhs | const T2\& | RHS 容器參照。 |

### 返回值

如果包含的元素和大小相符則返回 true，否則返回 false。

## 另請參閱

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)