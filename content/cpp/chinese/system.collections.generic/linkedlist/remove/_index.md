---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从列表中删除指定元素的第一次出现。
type: docs
weight: 196
url: /zh/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) method

从列表中删除指定的 **element** 的第一次出现。

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | const T\& | 要删除的元素。 |

### 返回值

如果找到了 **element** 并已删除，则返回 true；否则返回 false。

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) method

从列表中删除节点。

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要删除的节点。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [LinkedList](../)
* 类 [LinkedListNode](../../linkedlistnode/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)