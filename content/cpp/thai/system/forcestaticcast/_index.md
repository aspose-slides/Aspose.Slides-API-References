---
title: ForceStaticCast()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ทำการแคสท์สแตติกจริงบนอ็อบเจ็กต์ SmartPtr.
type: docs
weight: 2588
url: /th/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) ฟังก์ชัน

ทำการแคสท์สแตติกจริงบนอ็อบเจ็กต์ [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | พอยน์เตอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสท์หากการแคสท์ได้รับอนุญาต, มิฉะนั้นพฤติกรรมจะไม่กำหนด.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* โครงสร้าง [CastResult](../castresult/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)