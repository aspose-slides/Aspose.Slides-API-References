---
title: Cast_noexcept()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการแปลงประเภทบนวัตถุ SmartPtr.
type: docs
weight: 2497
url: /th/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) ฟังก์ชัน


ทำการแปลงประเภทบนวัตถุ [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภทของ pointee ที่เป็นเป้าหมาย. |
| TFrom | ประเภทของ pointee ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ตัวชี้ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาตหรือ nullptr มิฉะนั้น.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)