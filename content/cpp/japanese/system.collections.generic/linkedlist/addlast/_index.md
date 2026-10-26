---
title: AddLast()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素をリストの末尾に追加します。
type: docs
weight: 92
url: /ja/system.collections.generic/linkedlist/addlast/
---
## LinkedList::AddLast(const T\&) method


**element** をリストの末尾に追加します。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddLast(const T &element)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | const T\& | 追加する要素。 |

### 戻り値

新しいノード。

## LinkedList::AddLast(const SharedPtr\<LinkedListNode\<T\>\>\&) method


**newNode** をリストの末尾に追加します。

```cpp
void System::Collections::Generic::LinkedList<T>::AddLast(const SharedPtr<LinkedListNode<T>> &newNode)
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