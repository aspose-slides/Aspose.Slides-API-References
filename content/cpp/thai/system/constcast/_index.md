---
title: ConstCast()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จบการแคสต์ที่เลิกใช้แล้ว.
type: docs
weight: 2575
url: /th/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) ฟังก์ชัน


จบการแคสต์ที่เลิกใช้แล้ว

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | ประเภทของ pointee ที่ต้องการ |
| TFrom | ประเภทของ pointee ต้นฉบับ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | ตัวชี้ต้นฉบับ |

### ค่าที่คืนกลับ

ผลลัพธ์ของการแคสต์ถ้าการแคสต์ได้รับอนุญาต หรือ nullptr หากไม่อนุญาต
## หมายเหตุ


ทำ const cast บนวัตถุ [SmartPtr](../smartptr/) 
## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* โครงสร้าง [CastResult](../castresult/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)