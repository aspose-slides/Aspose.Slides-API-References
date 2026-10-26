---
title: Console
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีเมธอดสำหรับส่งออกข้อมูลไปยังสตรีมเอาต์พุตมาตรฐาน นี่เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ
type: docs
weight: 196
url: /th/system/console/
---
## คลาส Console

Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Console
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| static void [Beep](./beep/)() | ยังไม่ได้ดำเนินการ. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | ส่งคืน shared pointer ที่ชี้ไปยังอ็อบเจกต์ที่แทนสตรีมข้อผิดพลาดมาตรฐาน. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | ส่งคืน shared pointer ที่ชี้ไปยังอ็อบเจกต์ที่แทนสตรีมอินพุตมาตรฐาน. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | ส่งคืน shared pointer ที่ชี้ไปยังอ็อบเจกต์ที่แทนสตรีมเอาต์พุตมาตรฐาน. |
| static void [Mute](./mute/)(**bool**) | ปิดหรือเปิดสตรีมเอาต์พุตมาตรฐาน. |
| static void [ReadKey](./readkey/)() | ยังไม่ได้ดำเนินการ. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | ตั้งค่าคำบรรทัดหัวของหน้าต่างคอนโซล. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | กำหนดอ็อบเจกต์ที่ระบุให้กับคุณสมบัติ Error ของคลาส. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | กำหนดคุณสมบัติ In ให้เป็นอ็อบเจกต์ TextReader ที่ระบุ. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | กำหนดอ็อบเจกต์ที่ระบุให้กับคุณสมบัติ Out ของคลาส. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ส่งออกการแสดงผลเป็นสตริงของอ็อบเจกต์ที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**bool**) | ส่งออกการแสดงผลเป็นสตริงของค่า bool ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(char_t) | ส่งออกค่าตัวอักษรที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | ส่งออกการแสดงผลเป็นสตริงของอาร์เรย์อักขระที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | ส่งออกการแสดงผลเป็นสตริงของค่า [Decimal](../decimal/) ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**double**) | ส่งออกการแสดงผลเป็นสตริงของค่าจุดลอยแบบ double-precision ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**float**) | ส่งออกการแสดงผลเป็นสตริงของค่าจุดลอยแบบ single-precision ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**int32_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 32 บิต ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**int64_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 64 บิต ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const [String](../string/)\&) | ส่งออกอ็อบเจกต์สตริงที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const char_t *) | ส่งออก c-string ที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | ส่งออกการแสดงผลเป็นสตริงของค่า [TypeInfo](../typeinfo/) ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**uint32_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าตัวเลขจำนวนเต็มบวกแบบ unsigned 32-bit ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(**uint64_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าตัวเลขจำนวนเต็มบวกแบบ unsigned 64-bit ไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | ส่งออกการแสดงผลเป็นสตริงของช่วงที่ระบุของอาร์เรย์อักขระที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | ส่งออกการแสดงผลเป็นสตริงของอาร์กิวเมนต์ที่ระบุโดยจัดรูปตามรูปแบบที่ระบุไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | ส่งออกตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ส่งออกการแสดงผลเป็นสตริ่งของอ็อบเจกต์ที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**bool**) | ส่งออกการแสดงผลเป็นสตริงของค่า bool แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(char_t) | ส่งออกค่าตัวอักษรที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | ส่งออกการแสดงผลเป็นสตริงของอาร์เรย์อักขระที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | ส่งออกการแสดงผลเป็นสตริงของค่า [Decimal](../decimal/) แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**double**) | ส่งออกการแสดงผลเป็นสตริงของค่าจุดลอยแบบ double-precision แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**float**) | ส่งออกการแสดงผลเป็นสตริงของค่าจุดลอยแบบ single-precision แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**int32_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 32 บิต แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**int64_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 64 บิต แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | ส่งออกอ็อบเจกต์สตริงที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const char_t *) | ส่งออก c-string ที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | ส่งออกการแสดงผลเป็นสตริงของค่า [TypeInfo](../typeinfo/) แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**uint32_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าตัวเลขจำนวนเต็มบวกแบบ unsigned 32-bit แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(**uint64_t**) | ส่งออกการแสดงผลเป็นสตริงของค่าตัวเลขจำนวนเต็มบวกแบบ unsigned 64-bit แล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | ส่งออกการแสดงผลเป็นสตริงของช่วงที่ระบุของอาร์เรย์อักขระที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | ส่งออกการแสดงผลเป็นสตริงของอ็อบเจกต์ Exception ที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | ส่งออกการแสดงผลเป็นสตริงของอาร์กิวเมนต์ที่ระบุโดยจัดรูปตามรูปแบบที่ระบุแล้วตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีมเอาต์พุตมาตรฐาน. |
| static void [WriteLine](./writeline/)(const char *) |  |
## หมายเหตุ

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // พิมพ์ข้อความสวัสดี.
  Console::WriteLine(u"Hello, world!");

  // สร้างอินสแตนซ์ของคลาส 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // พิมพ์สมาชิกของอาร์เรย์.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
Hello, world!
1 2 3 4 5
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)