---
title: AbstractEqual()
second_title: Aspose.Slides for C++ API 参考
description: 比较两个未知类型的集合。
type: docs
weight: 14
url: /zh/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) 方法

比较两个未知类型的集合。

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | 左侧集合。 |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | 右侧集合。 |

### 返回值

如果集合匹配（例如两者均为 null），或大小相同且元素相同则返回 true，否则返回 false。

## 另见

* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)