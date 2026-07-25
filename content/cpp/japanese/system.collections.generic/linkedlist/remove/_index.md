---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された要素の最初の出現をリストから削除します。
type: docs
weight: 196
url: /ja/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) メソッド

指定された **element** の最初の出現をリストから削除します。

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | const T\& | 削除する要素。 |

### 戻り値

**element** が見つかり削除された場合は true、そうでない場合は false。

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) メソッド

リストから node を削除します。

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 削除するノード。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [LinkedList](../)
* クラス [LinkedListNode](../../linkedlistnode/)
* 名前空間 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)