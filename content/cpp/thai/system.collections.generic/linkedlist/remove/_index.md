---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบการเกิดครั้งแรกขององค์ประกอบที่ระบุออกจากรายการ.
type: docs
weight: 196
url: /th/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) method


ลบการเกิดครั้งแรกของ **element** ที่ระบุออกจากรายการ.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | const T\& | Element ที่จะลบ. |

### ค่าที่ส่งคืน

True หาก **element** ถูกพบและถูกลบ, false หากไม่พบ.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) method


ลบ node ออกจากรายการ.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node ที่จะลบ. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [LinkedList](../)
* คลาส [LinkedListNode](../../linkedlistnode/)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)