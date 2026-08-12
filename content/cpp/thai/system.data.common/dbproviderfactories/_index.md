---
title: DbProviderFactories
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "API เพื่อรับ DB provider factories. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr แล้วใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 53
url: /th/system.data.common/dbproviderfactories/
---
## DbProviderFactories คลาส


API เพื่อรับ DB provider factories. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ให้ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class DbProviderFactories
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | ดึง factory ของ DB provider ตามชื่อ. |
## ดูเพิ่มเติม

* เนมสเปซ [System::Data::Common](../)
* ไลบรารี [Aspose.Slides](../../)