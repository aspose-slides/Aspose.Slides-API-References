---
title: AddAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: リストのノードの後に要素を追加します。
type: docs
weight: 53
url: /ja/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) メソッド


リストの **node** の後に **element** を追加します。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 挿入するノード |
| element | const T\& | 追加する要素 |

### 戻り値

新しいノード。

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) メソッド


リストの **node** の後に **newNode** を追加します。

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 挿入するノード |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 追加する新しいノード |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [LinkedListNode](../../linkedlistnode/)
* クラス [LinkedList](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)