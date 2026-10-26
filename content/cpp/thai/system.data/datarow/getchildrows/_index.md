---
title: GetChildRows()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงแถวที่ถือว่าเป็นแถวลูกผ่านความสัมพันธ์ที่ระบุ.
type: docs
weight: 27
url: /th/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\) method

ดึงแถวที่ถือเป็นแถวลูกผ่านความสัมพันธ์ที่ระบุ.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | อ็อบเจกต์ความสัมพันธ์เพื่อระบุความสัมพันธ์ระหว่างแถวแม่และแถวลูก. |

### ค่าที่ส่งคืน

[Array](../../../system/array/) ของแถวลูกที่ดึงคืน.

## ดูเพิ่มเติม

* การพิมพ์ชนิด [ArrayPtr](../../../system/arrayptr/)
* การพิมพ์ชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [DataRow](../)
* คลาส [DataRelation](../../datarelation/)
* เนมสเปซ [System::Data](../../)
* ไลบรารี [Aspose.Slides](../../../)