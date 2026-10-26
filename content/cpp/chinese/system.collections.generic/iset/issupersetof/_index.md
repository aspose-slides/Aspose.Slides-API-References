---
title: IsSupersetOf()
second_title: Aspose.Slides C++ API 参考
description: 检查当前集合是否是其他容器的超集。
type: docs
weight: 79
url: /zh/system.collections.generic/iset/issupersetof/
---
## ISet::IsSupersetOf(IEnumerablePtr) 方法


检查当前集合是否是其他容器的超集。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsSupersetOf(IEnumerablePtr other)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 要检查的子集。 |

### 返回值

如果 **other** 中的所有元素都存在于集合中，则返回 true；否则返回 false。

## 参见

* 类型定义 [IEnumerablePtr](../ienumerableptr/)
* 类 [ISet](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)