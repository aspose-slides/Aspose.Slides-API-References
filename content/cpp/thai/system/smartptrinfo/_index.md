---
title: SmartPtrInfo
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คลาสบริการเพื่อทดสอบและแก้ไขเนื้อหาของ SmartPtr โดยไม่ต้องรู้ประเภทสุดท้าย ใช้สำหรับการเก็บกากและการตรวจจับการอ้างอิงแบบวนลูป เป็นต้น คิดว่าเป็น 'pointer to pointer' เราไม่สามารถใช้ SmartPtr's basetype ได้เพราะไม่มี; แทนที่จะนั้น เราใช้คลาส 'info' นี้
type: docs
weight: 1249
url: /th/system/smartptrinfo/
---
## SmartPtrInfo คลาส


Service คลาสเพื่อทดสอบและแก้ไขเนื้อหาของ [SmartPtr](../smartptr/)'s โดยไม่ต้องรู้ประเภทสุดท้าย ใช้สำหรับการเก็บกากและการตรวจจับการอ้างอิงแบบวนลูป เป็นต้น คิดว่าเป็น 'pointer to pointer' เราไม่สามารถใช้ basetype ของ [SmartPtr](../smartptr/) ได้เพราะไม่มี; แทนที่จะนั้น เราใช้คลาส 'info' นี้

```cpp
class SmartPtrInfo
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | รับออบเจ็กต์ดิบที่ตัวชี้อ้างอิงชี้ไป |
| [Object](../object/) * [getObject](./getobject/)() const | รับออบเจ็กต์ที่ตัวชี้อ้างอิงชี้ไป |
| [Object](../object/) * [getOwned](./getowned/)() const | รับตัวชี้ที่เป็นของออบเจ็กต์ |
|  [operator bool](./operator_bool/)() const | ตรวจสอบว่าอ็อบเจ็กต์ info ชี้ไปยังตัวชี้ที่ไม่เป็น null หรือไม่ |
| **bool** [operator!](./operator_not/)() const | ตรวจสอบว่าอ็อบเจ็กต์ info ไม่ได้ชี้ไปยังตัวชี้ที่ไม่เป็น null |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | อนุญาตให้เรียกเมธอดของ [Object](../object/) ที่ตัวชี้อ้างอิงชี้ไป |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | เปรียบเทียบค่าน้อยของค่าตัวชี้ที่อ้างอิงโดยอ็อบเจ็กต์ info สองตัว |
|  [SmartPtrInfo](./smartptrinfo/)() | สร้างอ็อบเจ็กต์ [SmartPtrInfo](./) ว่าง |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | สร้างอ็อบเจ็กต์ [SmartPtrInfo](./) พร้อมข้อมูลเกี่ยวกับ smart pointer ที่เฉพาะเจาะจง |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)