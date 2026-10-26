---
title: AddLast()
second_title: Aspose.Slides for C++ API 參考文件
description: 將元素加入列表的末端。
type: docs
weight: 92
url: /zh-hant/system.collections.generic/linkedlist/addlast/
---
## LinkedList::AddLast(const T\&) 方法

將 **element** 加到列表的末端。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddLast(const T &element)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | const T\& | 要加入的元素。 |

### 返回值

新節點。

## LinkedList::AddLast(const SharedPtr\<LinkedListNode\<T\>\>\&) 方法

將 **newNode** 加到列表的末端。

```cpp
void System::Collections::Generic::LinkedList<T>::AddLast(const SharedPtr<LinkedListNode<T>> &newNode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要加入的新節點。 |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [LinkedListNode](../../linkedlistnode/)
* 類別 [LinkedList](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)