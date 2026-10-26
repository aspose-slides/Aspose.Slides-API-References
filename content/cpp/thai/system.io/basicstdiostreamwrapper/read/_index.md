---
title: Read()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: หากโหมดการห่อหุ้มเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม, มิฉะนั้นจะอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท uint8_t. เขียนผลลัพธ์ของการอ่านลงในอาร์เรย์ไบต์ที่ระบุ.
type: docs
weight: 66
url: /th/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

ถ้าโหมดการห่อหุ้มเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม, หากไม่ใช่จะอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท **uint8_t**. เขียนผลลัพธ์ของการอ่านไปยังอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่จะเขียนไบต์ที่อ่านได้ไป |
| offset | **int32_t** | ตำแหน่งเริ่มต้นใน **buffer** ที่เริ่มเขียน (นับจาก 0) |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืน

จำนวนไบต์หรืออักขระที่อ่านได้

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | วิวอาร์เรย์ไบต์ที่จะเขียนไบต์ที่อ่านได้ไป |
| offset | **int32_t** | ตำแหน่งเริ่มต้นใน **buffer** ที่เริ่มเขียน (นับจาก 0) |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืน

จำนวนไบต์ที่อ่านได้

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [BasicSTDIOStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)