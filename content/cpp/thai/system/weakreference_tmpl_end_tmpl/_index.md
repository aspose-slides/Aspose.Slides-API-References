---
title: WeakReference<>
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนค่าการอ้างอิงแบบอ่อน ซึ่งอ้างอิงอ็อบเจ็กต์พร้อมยังอนุญาตให้อ็อบเจ็กต์นั้นถูกลบได้
type: docs
weight: 1522
url: /th/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> คลาส

แทนค่าการอ้างอิงแบบอ่อน ซึ่งอ้างอิงอ็อบเจ็กต์พร้อมยังอนุญาตให้อ็อบเจ็กต์นั้นถูกลบได้

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | รับข้อมูลว่ามีการลบอ็อบเจ็กต์ที่อ้างอิงโดยอ็อบเจ็กต์ WeakReference ปัจจุบันหรือไม่ |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | รับอ็อบเจ็กต์ (เป้าหมาย) ที่อ้างอิงโดยอ็อบเจ็กต์ WeakReference ปัจจุบัน |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ตั้งค่าอ็อบเจ็กต์ (เป้าหมาย) ที่อ้างอิงโดยอ็อบเจ็กต์ WeakReference ปัจจุบัน |
|  [WeakReference](./weakreference/)() | คอนสตรัคเตอร์เริ่มต้น |
|  [WeakReference](./weakreference/)(std::nullptr_t) | คอนสตรัคเตอร์จาก nullptr |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | กำหนดค่าอินสแตนซ์ใหม่ของ WeakReference คลาส โดยอ้างอิงอ็อบเจ็กต์ที่ระบุ |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | กำหนดค่าอินสแตนซ์ใหม่ของ WeakReference คลาส โดยอ้างอิงอ็อบเจ็กต์ที่ระบุ |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)