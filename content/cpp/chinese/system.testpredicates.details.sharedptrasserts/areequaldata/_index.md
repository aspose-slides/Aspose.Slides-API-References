---
title: AreEqualData()
second_title: Aspose.Slides for C++ API 参考
description: "使用 System::Object::Equals 对元素进行相等比较，适用于 SmartPtr 元素。"
type: docs
weight: 14
url: /zh/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

使用 [System::Object::Equals](../../system/object/equals/) 对元素进行相等比较。适用于 [SmartPtr](../../system/smartptr/) 元素。

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧容器类型。 |
| T2 | 右侧容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | const T1\& | 左侧容器引用。 |
| rhs | const T2\& | 右侧容器引用。 |

### 返回值

如果包含的元素和大小匹配则返回 true，否则返回 false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

使用 operator == 对元素进行相等比较。适用于非 SmartPtr 元素。

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧容器类型。 |
| T2 | 右侧容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | const T1\& | 左侧容器。 |
| rhs | const T2\& | 右侧容器。 |

### 返回值

如果包含的元素和大小匹配则返回 true，否则返回 false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function

比较两个相同类型的容器的相等性。适用于非 SmartPtr 元素。

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧容器类型。 |
| T2 | 右侧容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | const T\& | 左侧容器。 |
| rhs | const T\& | 右侧容器。 |

### 返回值

如果包含的元素和大小匹配则返回 true，否则返回 false。

## 另请参见

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)