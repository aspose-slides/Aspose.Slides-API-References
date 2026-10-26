---
title: CopyTo()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คัดลอกองค์ประกอบของรายการไปยังอาเรย์ที่มีอยู่แล้ว
type: docs
weight: 209
url: /th/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) เมธอด

คัดลอกองค์ประกอบของรายการไปยังอาเรย์ที่มีอยู่แล้ว

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | อาเรย์ปลายทาง |
| arrayIndex | int | ดัชนีเริ่มต้นของอาเรย์ปลายทาง |

## List::CopyTo(const System::ArrayPtr\<T\>\&) เมธอด


คัดลอกทุกองค์ประกอบไปยังอาเรย์ที่มีอยู่แล้ว

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) เพื่อคัดลอกองค์ประกอบเข้าไป |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) เมธอด


คัดลอกองค์ประกอบเริ่มตั้งแต่ดัชนีที่ระบุไปยังอาเรย์ที่มีอยู่แล้ว

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นแบบ 0 ขององค์ประกอบในรายการที่อธิบายโดยอ็อบเจกต์ปัจจุบันเพื่อเริ่มคัดลอก |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) เพื่อคัดลอกองค์ประกอบเข้าไป |
| arrayIndex | int | ตำแหน่งเริ่มต้นในอาเรย์ปลายทาง |
| count | int | จำนวนองค์ประกอบที่ต้องคัดลอก |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [List](../)
* เนมสเปซ [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)