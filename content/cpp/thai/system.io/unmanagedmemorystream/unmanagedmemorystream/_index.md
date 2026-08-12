---
title: UnmanagedMemoryStream()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของ UnmanagedMemoryStream.
type: docs
weight: 118
url: /th/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pointer | **uint8_t** * | ตัวชี้ไปยังบัฟเฟอร์ที่ไม่ได้จัดการ |
| length | **int64_t** | ขนาดของบัฟเฟอร์ที่ไม่ได้จัดการเป็นไบต์ |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pointer | **uint8_t** * | ตัวชี้ไปยังบัฟเฟอร์ที่ไม่ได้จัดการ |
| length | **int64_t** | ขนาดของบัฟเฟอร์ที่ไม่ได้จัดการเป็นไบต์ |
| capacity | **int64_t** | จำนวนหน่วยความจำทั้งหมดที่กำหนดให้สตรีม |
| access | [FileAccess](../../fileaccess/) | ระบุว่าสตรีมควรเป็นอ่านอย่างเดียว, เขียนอย่างเดียว หรือทั้งสองอย่าง |

## ดูเพิ่มเติม

* Enum [FileAccess](../../fileaccess/)
* คลาส [UnmanagedMemoryStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)