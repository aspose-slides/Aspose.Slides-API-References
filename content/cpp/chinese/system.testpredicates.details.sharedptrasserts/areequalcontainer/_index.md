---
title: AreEqualContainer()
second_title: Aspose.Slides for C++ API 参考
description: 使用 operator == 对元素进行相等比较的两个容器。适用于非 SmartPtr 元素。
type: docs
weight: 1
url: /zh/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1&, const T2&) function

使用 operator == 对元素进行相等比较的两个容器。适用于非 SmartPtr 元素。

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧容器类型。 |
| T2 | 右侧容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | const T1& | 左侧容器。 |
| rhs | const T2& | 右侧容器。 |

### 返回值

如果包含的元素和大小匹配则为 true，否则为 false。

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1&, const T2&) function

使用 [System::Object::Equals](../../system/object/equals/) 对元素进行相等比较的两个容器。适用于 [SmartPtr](../../system/smartptr/) 元素。

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧容器类型。 |
| T2 | 右侧容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | const T1& | 左侧容器引用。 |
| rhs | const T2& | 右侧容器引用。 |

### 返回值

如果包含的元素和大小匹配则为 true，否则为 false。

## 另请参见

* 结构体 [IsSmartPtr](../../system/issmartptr/)
* 命名空间 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 库 [Aspose.Slides](../../)