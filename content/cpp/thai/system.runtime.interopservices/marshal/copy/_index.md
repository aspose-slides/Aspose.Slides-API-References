---
title: Copy()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดำเนินการตามความหมายของ public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics.
type: docs
weight: 1
url: /th/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) เมธอด

ดำเนินการตามความหมายของ public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| container | ประเภทคอนเทนเนอร์ปลายทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | const IntPtr | ตัวชี้ข้อมูลต้นทาง. |
| destination | container\&& | คอนเทนเนอร์ที่จะคัดลอกข้อมูลเข้าไป. |
| startIndex | int | ดัชนีเริ่มต้นของต้นทาง. |
| length | int | จำนวนองค์ประกอบที่จะคัดลอก. |

## Marshal::Copy(const void *, container\&&, int, int) เมธอด

ดำเนินการตามความหมายของ public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| container | ประเภทคอนเทนเนอร์ปลายทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | const void * | ตัวชี้ข้อมูลต้นทาง. |
| destination | container\&& | คอนเทนเนอร์ที่จะคัดลอกข้อมูลเข้าไป. |
| startIndex | int | ดัชนีเริ่มต้นของต้นทาง. |
| length | int | จำนวนองค์ประกอบที่จะคัดลอก. |

## Marshal::Copy(const container\&, int, void *, int) เมธอด

ดำเนินการตามความหมายของ public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| container | ประเภทคอนเทนเนอร์ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | const container\& | ตัวชี้ข้อมูลต้นทาง. |
| startIndex | int | ดัชนีเริ่มต้นของต้นทาง. |
| destination | void * | ตัวชี้ข้อมูลปลายทาง. |
| length | int | จำนวนองค์ประกอบที่จะคัดลอก. |

## Marshal::Copy(const container\&, int, IntPtr, int) เมธอด

ดำเนินการตามความหมายของ public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| container | ประเภทคอนเทนเนอร์ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | const container\& | ตัวชี้ข้อมูลต้นทาง. |
| startIndex | int | ดัชนีเริ่มต้นของต้นทาง. |
| destination | IntPtr | ตัวชี้ข้อมูลปลายทาง. |
| length | int | จำนวนองค์ประกอบที่จะคัดลอก. |

## ดูเพิ่มเติม

* คลาส [Marshal](../)
* เนมสเปซ [System::Runtime::InteropServices](../../)
* ไลบรารี [Aspose.Slides](../../../)