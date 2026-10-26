---
title: AddBefore()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มองค์ประกอบก่อนโหนดของรายการ.
type: docs
weight: 66
url: /th/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) เมธอด


เพิ่ม **element** ก่อน **node** ของรายการ.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | โหนดที่ต้องการแทรกก่อน |
| element | const T\& | องค์ประกอบที่จะเพิ่ม |

### ค่าที่คืน

โหนดใหม่.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) เมธอด


เพิ่ม **newNode** ก่อน **node** ของรายการ.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | โหนดที่ต้องการแทรกก่อน |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | โหนดใหม่ที่จะเพิ่ม |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [LinkedListNode](../../linkedlistnode/)
* คลาส [LinkedList](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)