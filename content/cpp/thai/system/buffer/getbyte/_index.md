---
title: GetByte()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตีความอาเรย์ที่ระบุประเภทเป็นอาเรย์ไบต์แบบดิบและดึงค่าบายต์ที่ออฟเซ็ตไบต์ที่ระบุ
type: docs
weight: 27
url: /th/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) เมธอด


ตีความอาเรย์ที่ระบุประเภทเป็นอาเรย์ไบต์แบบดิบและดึงค่าบายต์ที่ออฟเซ็ตไบต์ที่ระบุ

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของอาเรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | อาเรย์เป้าหมาย |
| index | int | ออฟเซ็ตของไบต์ที่ต้องดึงโดยเริ่มจากศูนย์ |

### ค่าที่ส่งกลับ

ค่าบายต์ที่ตำแหน่งที่ระบุ

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) เมธอด


ตีความอาเรย์ที่ระบุประเภทเป็นอาเรย์ไบต์แบบดิบและดึงค่าบายต์ที่ออฟเซ็ตไบต์ที่ระบุ

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของอาเรย์วิว |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | อาเรย์วิวเป้าหมาย |
| index | int | ออฟเซ็ตของไบต์ที่ต้องดึงโดยเริ่มจากศูนย์ |

### ค่าที่ส่งกลับ

ค่าบายต์ที่ตำแหน่งที่ระบุ

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) เมธอด


ตีความอาเรย์ที่ระบุประเภทเป็นอาเรย์ไบต์แบบดิบและดึงค่าบายต์ที่ออฟเซ็ตไบต์ที่ระบุ

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของสแตกอาเรย์ |
| N | ขนาดของสแตกอาเรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | สแตกอาเรย์เป้าหมาย |
| index | int | ออฟเซ็ตของไบต์ที่ต้องดึงโดยเริ่มจากศูนย์ |

### ค่าที่ส่งกลับ

ค่าบายต์ที่ตำแหน่งที่ระบุ

## ดูเพิ่มเติม

* ประเภทกำหนด [SharedPtr](../../sharedptr/)
* คลาส [Array](../../array/)
* คลาส [Buffer](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)