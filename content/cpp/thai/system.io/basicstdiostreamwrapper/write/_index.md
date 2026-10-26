---
title: Write()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากโหมดการห่อหุ้มเป็น binary จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุลงใน stream, มิฉะนั้นจะแปลงช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ลงใน stream.
type: docs
weight: 79
url: /th/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

หากโหมดการห่อหุ้มเป็นไบนารี จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุลงในสตรีม มิฉะนั้นจะแปลงช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ลงในสตรีม

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์เพื่อเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นจาก 0 ของ **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | วิวอาร์เรย์ที่บรรจุไบต์เพื่อเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นจาก 0 ของ **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [BasicSTDIOStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)