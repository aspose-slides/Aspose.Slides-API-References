---
title: AddAfter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่ม element หลัง node ของรายการ.
type: docs
weight: 53
url: /th/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

Adds **element** after **node** of the list.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | โหนดที่จะแทรกหลังจาก |
| element | const T\& | element ที่จะเพิ่ม |

### ค่าที่คืน

New node.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

Adds **newNode** after **node** of the list.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | โหนดที่จะแทรกหลังจาก |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | โหนดใหม่ที่จะเพิ่ม |

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [LinkedListNode](../../linkedlistnode/)
* คลาส [LinkedList](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)