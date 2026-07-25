---
title: AddFirst()
second_title: Aspose.Slides for C++ API リファレンス
description: リストの先頭に要素を追加します。
type: docs
weight: 79
url: /ja/system.collections.generic/linkedlist/addfirst/
---
## LinkedList::AddFirst(const T\&) メソッド

リストの先頭に **element** を追加します。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddFirst(const T &element)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | const T\& | 追加する要素。 |

### 戻り値

新しいノード。

## LinkedList::AddFirst(const SharedPtr\<LinkedListNode\<T\>\>\&) メソッド

リストの先頭に **newNode** を追加します。

```cpp
void System::Collections::Generic::LinkedList<T>::AddFirst(const SharedPtr<LinkedListNode<T>> &newNode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 追加する新しいノード。 |

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)