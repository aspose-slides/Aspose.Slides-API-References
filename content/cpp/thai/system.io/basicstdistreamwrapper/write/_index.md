---
title: Write()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากโหมดการห่อหุ้มเป็นแบบไบนารี จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุลงในสตรีม, มิฉะนั้นจะเปลี่ยนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ลงในสตรีม ไม่รองรับ!
type: docs
weight: 79
url: /th/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

หากโหมดการห่อหุ้มเป็นแบบไบนารี จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุลงในสตรีม, มิฉะนั้นจะเปลี่ยนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ลงในสตรีม ไม่รองรับ!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่ประกอบด้วยไบต์ที่จะเขียน. |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ของอีลีเมนต์ใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น. |
| count | **int32_t** | จำนวนอีลีเมนต์ในช่วงย่อยที่จะเขียน. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุลงในสตรีม.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | วิวของอาเรย์ที่ประกอบด้วยไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ของอีลีเมนต์ใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนอีลีเมนต์ในช่วงย่อยที่จะเขียน |

## ดูเพิ่มเติม

* การกำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* คลาส [BasicSTDIStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)