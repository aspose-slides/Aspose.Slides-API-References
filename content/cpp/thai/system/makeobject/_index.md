---
title: MakeObject()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอ็อบเจ็กต์บน heap และคืนค่าตัวชี้แบบ shared ไปยังอ็อบเจ็กต์นั้น
type: docs
weight: 2887
url: /th/system/makeobject/
---
## System::MakeObject(Args\&&...) ฟังก์ชัน

สร้างอ็อบเจ็กต์บน heap และคืนค่าตัวชี้แบบ shared ไปยังอ็อบเจ็กต์นั้น

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | คลาสที่จะสร้างตัวอย่าง |
| Args | ประเภทของอาร์กิวเมนต์ของคอนสตรัคเตอร์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | Args\&&... | อาร์กิวเมนต์ของคอนสตรัคเตอร์ |

### ค่าที่คืนกลับ

[SmartPtr](../smartptr/) ไปยังอ็อบเจ็กต์ที่สร้างใหม่, เสมอในโหมด shared

## System::MakeObject(Args\&&...) ฟังก์ชัน

สร้างอ็อบเจ็กต์บน heap และคืนค่าตัวชี้แบบ shared ไปยังอ็อบเจ็กต์นั้น

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [SmartPtr](../smartptr/) ไปยังคลาสที่จะสร้างตัวอย่าง |
| Args | ประเภทของอาร์กิวเมนต์ของคอนสตรัคเตอร์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | Args\&&... | อาร์กิวเมนต์ของคอนสตรัคเตอร์ |

### ค่าที่คืนกลับ

[SmartPtr](../smartptr/) ไปยังอ็อบเจ็กต์ที่สร้างใหม่, เสมอในโหมด shared

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* โครงสร้าง [IsSmartPtr](../issmartptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)