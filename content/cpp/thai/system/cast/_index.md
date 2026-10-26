---
title: Cast()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการแคสต์บนอ็อบเจ็กต์ SmartPtr.
type: docs
weight: 2510
url: /th/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) ฟังก์ชัน


ทำการแคสต์บนวัตถุ [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภทของพอยน์ตี้เป้าหมาย |
| TFrom | ประเภทของพอยน์ตี้ต้นทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ตัวชี้ต้นทาง |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)