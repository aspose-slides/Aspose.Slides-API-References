---
title: GetDelegateForFunctionPointer()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงตัวชี้ฟังก์ชันที่ไม่ได้จัดการให้เป็น delegate ของประเภทที่ระบุ
type: docs
weight: 14
url: /th/system.runtime.interopservices/marshal/getdelegateforfunctionpointer/
---
## Marshal::GetDelegateForFunctionPointer(IntPtr) method


แปลงตัวชี้ฟังก์ชันที่ไม่ได้จัดการให้เป็น delegate ของประเภทที่ระบุ

```cpp
template<typename TDelegate> static TDelegate System::Runtime::InteropServices::Marshal::GetDelegateForFunctionPointer(IntPtr ptr)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TDelegate | ประเภทของ delegate ที่จะคืนค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| ptr | IntPtr | ตัวชี้ฟังก์ชันที่ไม่ได้จัดการเพื่อแปลง |

### ค่าที่คืน

อินสแตนซ์ของประเภท delegate ที่ระบุ

## หมายเหตุ



รหัสตัวอย่างแบบหยาบสำหรับการใช้งานในอนาคต 

## ดูเพิ่มเติม

* คลาส [Marshal](../)
* เนมสเปซ [System::Runtime::InteropServices](../../)
* ไลบรารี [Aspose.Slides](../../../)