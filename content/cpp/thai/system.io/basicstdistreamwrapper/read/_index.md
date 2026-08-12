---
title: Read()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: หากโหมดการห่อหุ้มเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม, ในกรณีอื่นจะอ่านจำนวนอักขระที่ระบุและแปลงเป็นชนิด uint8_t. เขียนผลลัพธ์ของการอ่านไปยังอาร์เรย์ไบต์ที่ระบุ.
type: docs
weight: 66
url: /th/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

ถ้าโหมดการห่อหุ้มเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม, ในกรณีอื่นจะอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท **uint8_t**. เขียนผลลัพธ์ของการอ่านไปยังอาร์เรย์ไบต์ที่ระบุ.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่าน |
| offset | **int32_t** | ตำแหน่งเริ่มต้นจาก 0 ใน **buffer** ที่จะเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องอ่าน |

### ค่าที่ส่งกลับ

จำนวนไบต์หรืออักขระที่อ่าน

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังอาร์เรย์ไบต์ที่ระบุ.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | วิวของอาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่าน |
| offset | **int32_t** | ตำแหน่งเริ่มต้นจาก 0 ใน **buffer** ที่จะเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องอ่าน |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่อ่าน

## ดูเพิ่มเติม

* ประเภทนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [BasicSTDIStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)