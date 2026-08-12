---
title: FieldAttributes
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: คุณลักษณะฟิลด์ที่สะท้อน
type: docs
weight: 170
url: /th/system.reflection/fieldattributes/
---
## FieldAttributes enum

Reflected field attributes.

```cpp
enum class FieldAttributes
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| FieldAccessMask | 7 | มาสก์การเข้าถึงสมาชิก ใช้มาสก์นี้เพื่อดึงข้อมูลการเข้าถึง |
| PrivateScope | 0 | สมาชิกที่ไม่สามารถอ้างอิงได้ |
| Private | 1 | สมาชิกแบบส่วนตัว |
| FamANDAssem | 2 | สมาชิกแบบส่วนตัวและมีขอบเขตของแอสเซมบลี |
| Assembly | 3 | สมาชิกที่มีขอบเขตของแอสเซมบลี |
| Family | 4 | สมาชิกที่เข้าถึงได้โดยประเภทและชนิดย่อย |
| FamORAssem | 5 | สมาชิกที่เข้าถึงได้โดยประเภท ชนิดย่อย และแอสเซมบลี |
| Public | 6 | สมาชิกที่เข้าถึงได้โดยใครก็ได้ |
| Static | 16 | สมาชิกแบบสแตติกซึ่งเป็นตรงข้ามกับสมาชิกแบบอินสแตนซ์ |
| InitOnly | 32 | สมาชิกคอนสท์ที่สามารถกำหนดค่าได้เพียงครั้งเดียวแต่ไม่สามารถเปลี่ยนแปลงได้ |
| Literal | 64 | สมาชิกคอนสท์ที่กำหนดค่าที่เวลาคอมไพล์ |
| NotSerialized | 128 | สมาชิกที่ไม่ได้ทำการซีเรียลไลซ์ |
| SpecialName | 512 | ฟิลด์พิเศษของหนึ่งในชื่อด้านล่าง |
| PinvokeImpl | 8192 | การทำงานที่ส่งต่อผ่าน Interop |
| ReservedMask | 38144 |แฟล็กที่สงวนไว้สำหรับการใช้ใน runtime เท่านั้น |
| RTSpecialName | 1024 | Runtime ควรตรวจสอบการเข้ารหัสชื่อ |
| HasFieldMarshal | 4096 | มีข้อมูลการมาร์แชลลิง |
| HasDefault | 32768 | มีค่าเริ่มต้น |
| HasFieldRVA | 256 | มี RVA |

## ดูเพิ่มเติม

* เนมสเปซ [System::Reflection](../)
* ไลบรารี [Aspose.Slides](../../)