---
title: Read()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: หากโหมดการห่อหุ้มเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม มิฉะนั้นจะอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท uint8_t เขียนผลลัพธ์ของการอ่านลงในอาเรย์ไบต์ที่ระบุ ไม่สนับสนุน!
type: docs
weight: 66
url: /th/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


ถ้าโหมดการห่อหุ้มเป็นแบบไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม มิฉะนั้นจะอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท **uint8_t** เขียนผลลัพธ์ของการอ่านลงในอาเรย์ไบต์ที่ระบุ ไม่สนับสนุน!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ไบต์ที่จะเขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งตั้งต้นจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งคืน

จำนวนไบต์หรืออักขระที่อ่านได้

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาเรย์ไบต์ที่จะเขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งตั้งต้นจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งคืน

จำนวนไบต์ที่อ่านได้

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [BasicSTDOStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* Library [Aspose.Slides](../../../)