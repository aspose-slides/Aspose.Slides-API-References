---
title: ByteLength()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดจำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ
type: docs
weight: 14
url: /th/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) เมธอด


กำหนดจำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | อาร์เรย์ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) เมธอด


กำหนดจำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของวิวอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | วิวอาร์เรย์ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของวิวอาร์เรย์ที่ระบุ

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) เมธอด


กำหนดจำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของสแตกอาร์เรย์ |
| N | ขนาดของสแตกอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | สแตกอาร์เรย์ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ใช้โดยองค์ประกอบทั้งหมดของสแตกอาร์เรย์ที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)