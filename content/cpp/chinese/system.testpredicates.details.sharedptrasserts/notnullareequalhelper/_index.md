---
title: NotNullAreEqualHelper()
second_title: Aspose.Slides C++ API 参考
description: 对抽象集合进行相等比较。
type: docs
weight: 66
url: /zh/system.testpredicates.details.sharedptrasserts/notnullareequalhelper/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) 函数

对抽象集合进行相等比较。

```cpp
template<typename T> bool System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 左侧值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 右侧值。 |

### 返回值

gtest 风格的断言结果。

## 另请参见

* 类型别名 [SharedPtr](../../system/sharedptr/)
* 类 [ICollection](../../system.collections.generic/icollection/)
* 命名空间 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 库 [Aspose.Slides](../../)