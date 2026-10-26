---
title: Clear()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: ไม่รองรับเนื่องจากอาร์เรย์ที่แทนโดยออบเจ็กต์ปัจจุบันเป็นแบบอ่านอย่างเดียว.
type: docs
weight: 53
url: /th/system/array/clear/
---
## Array::Clear() เมธอด

Not supported because the array represented by the current object is read-only.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) เมธอด

Replaces **count** values starting at the **startIndex** index in the specified array with default values.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Type | ประเภทขององค์ประกอบในอาร์เรย์เป้าหมาย |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | อาร์เรย์เป้าหมาย |
| startIndex | int | [Index](../../index/) ที่ใช้เริ่มแทนที่รายการ |
| count | int | จำนวนรายการที่จะถูกแทนที่ |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* เมธอด [Type](../../object/type/)
* คลาส [Array](../)
* เนมส페ซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)