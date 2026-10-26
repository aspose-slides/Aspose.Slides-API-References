---
title: IndexOf()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดดัชนีของการปรากฏครั้งแรกของรายการที่ระบุในอาร์เรย์.
type: docs
weight: 131
url: /th/system/array/indexof/
---
## Array::IndexOf(const T\&) const เมธอด

กำหนดดัชนีของการปรากฏครั้งแรกของรายการที่ระบุในอาร์เรย์

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | const T\& | ดัชนีของรายการที่ต้องกำหนด |

### ค่าที่ส่งคืน

[Index](../../index/) ของการพบครั้งแรกของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) เมธอด

กำหนดดัชนีของการพบครั้งแรกของรายการที่ระบุในอาร์เรย์

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ArrayType | ชนิดขององค์ประกอบในอาร์เรย์เป้าหมาย |
| ValueType | ชนิดของรายการที่ต้องการค้นหาในอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) เพื่อค้นหารายการที่ระบุใน |
| value | const [ValueType](../valuetype/)\& | ดัชนีของรายการที่ต้องกำหนด |

### ค่าที่ส่งคืน

[Index](../../index/) ของการพบครั้งแรกของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) เมธอด

กำหนดดัชนีของการพบครั้งแรกของรายการที่ระบุในอาร์เรย์โดยเริ่มจากดัชนีที่ระบุ

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ArrayType | ชนิดขององค์ประกอบในอาร์เรย์เป้าหมาย |
| ValueType | ชนิดของรายการที่ต้องการค้นหาในอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) เพื่อค้นหารายการที่ระบุใน |
| value | const [ValueType](../valuetype/)\& | ดัชนีของรายการที่ต้องกำหนด |
| startIndex | int | [Index](../../index/) ที่การค้นหาเริ่มต้น |

### ค่าที่ส่งคืน

[Index](../../index/) ของการพบครั้งแรกของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) เมธอด

กำหนดดัชนีของการพบครั้งแรกของรายการที่ระบุในช่วงของรายการของอาร์เรย์ที่ระบุโดยดัชนีเริ่มต้นและจำนวนองค์ประกอบในช่วง

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ArrayType | ชนิดขององค์ประกอบในอาร์เรย์เป้าหมาย |
| ValueType | ชนิดของรายการที่ต้องการค้นหาในอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) เพื่อค้นหารายการที่ระบุใน |
| value | const [ValueType](../valuetype/)\& | ดัชนีของรายการที่ต้องกำหนด |
| startIndex | int | [Index](../../index/) ที่การค้นหาเริ่มต้น |
| count | int | จำนวนขององค์ประกอบในช่วงที่ต้องการค้นหา |

### ค่าที่ส่งคืน

[Index](../../index/) ของการพบครั้งแรกของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)