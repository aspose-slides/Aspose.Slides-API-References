---
title: Buffer
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีเมธอดที่จัดการอาร์เรย์ไบต์ดิบ. เป็นประเภทแบบ static ที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ.
type: docs
weight: 144
url: /th/system/buffer/
---
## คลาส Buffer

มีเมธอดที่จัดการอาร์เรย์ไบต์ดิบ. เป็นประเภทแบบ static ที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ

```cpp
class Buffer
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | คัดลอกจำนวนไบต์ที่ระบุจากบัฟเฟอร์ต้นทางไปยังบัฟเฟอร์ปลายทาง. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | แปลอาร์เรย์ที่กำหนดประเภทสองชุดเป็นอาร์เรย์ไบต์ดิบและคัดลอกข้อมูลจากหนึ่งไปยังอีกหนึ่ง. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | กำหนดจำนวนไบต์ที่ใช้งานโดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | กำหนดจำนวนไบต์ที่ใช้งานโดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | กำหนดจำนวนไบต์ที่ใช้งานโดยองค์ประกอบทั้งหมดของอาร์เรย์ที่ระบุ. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | แปลอาร์เรย์ที่กำหนดประเภทเป็นอาร์เรย์ไบต์ดิบและดึงค่าจากไบต์ที่ออฟเซ็ตตามที่ระบุ. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | แปลอาร์เรย์ที่กำหนดประเภทเป็นอาร์เรย์ไบต์ดิบและดึงค่าจากไบต์ที่ออฟเซ็ตตามที่ระบุ. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | แปลอาร์เรย์ที่กำหนดประเภทเป็นอาร์เรย์ไบต์ดิบและดึงค่าจากไบต์ที่ออฟเซ็ตตามที่ระบุ. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | แปลอาร์เรย์ที่กำหนดประเภทเป็นอาร์เรย์ไบต์ดิบและกำหนดค่าบิตที่ออฟเซ็ตที่ระบุ. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | แปลอาร์เรย์ที่กำหนดประเภทเป็นอาร์เรย์ไบต์ดิบและกำหนดค่าบิตที่ออฟเซ็ตที่ระบุ. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | แปลอาร์เรย์ที่กำหนดประเภทเป็นอาร์เรย์ไบต์ดิบและกำหนดค่าบิตที่ออฟเซ็ตที่ระบุ. |

## หมายเหตุ



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // สร้างและเติมอาร์เรย์.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // พิมพ์รายการในอาร์เรย์.
  Print(first, SIZE);

  // สร้างอาร์เรย์ที่มีส่วนหนึ่งของอาร์เรย์แรก.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // พิมพ์รายการของอาร์เรย์ที่สอง.
  Print(second, SIZE / 2);

  // ตั้งค่าชิ้นส่วนที่ตำแหน่ง 0 แล้วพิมพ์รายการในอาร์เรย์.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)