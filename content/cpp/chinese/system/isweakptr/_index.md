---
title: IsWeakPtr
second_title: Aspose.Slides C++ API 参考
description: "特性类用于检查特定类是否是 System::WeakPtr 的特化。不检查实例是否实际处于弱模式。"
type: docs
weight: 1730
url: /zh/system/isweakptr/
---
## IsWeakPtr 结构体


特性类用于检查特定类是否是 [System::WeakPtr](../weakptr/) 的特化。不检查实例是否实际处于弱模式。

```cpp
template<class T>class IsWeakPtr : public System::detail::is_a<T, System::WeakPtr>
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被测试的类型。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)