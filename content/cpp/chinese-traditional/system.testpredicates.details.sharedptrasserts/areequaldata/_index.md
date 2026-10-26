---
title: AreEqualData()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: "使用 System::Object::Equals 在元素上對兩個容器進行相等比較。適用於 SmartPtr 元素。"
type: docs
weight: 14
url: /zh-hant/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) 函式


使用 [System::Object::Equals](../../system/object/equals/) 在元素上進行相等比較兩個容器。適用於 [SmartPtr](../../system/smartptr/) 元素。

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T1 | LHS 容器類型。 |
| T2 | RHS 容器類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS 容器參考。 |
| rhs | const T2\& | RHS 容器參考。 |

### 回傳值

如果包含的元素與大小相符則回傳 true，否則回傳 false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) 函式


使用 operator == 在元素上進行相等比較兩個容器。適用於非 SmartPtr 元素。

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T1 | LHS 容器類型。 |
| T2 | RHS 容器類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS 容器。 |
| rhs | const T2\& | RHS 容器。 |

### 回傳值

如果包含的元素與大小相符則回傳 true，否則回傳 false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) 函式


使用相等比較兩個相同類型的容器。適用於非 SmartPtr 元素。

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T1 | LHS 容器類型。 |
| T2 | RHS 容器類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T\& | LHS 容器。 |
| rhs | const T\& | RHS 容器。 |

### 回傳值

如果包含的元素與大小相符則回傳 true，否則回傳 false。

## 相關參考

* 結構 [IsSmartPtr](../../system/issmartptr/)
* 命名空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 函式庫 [Aspose.Slides](../../)