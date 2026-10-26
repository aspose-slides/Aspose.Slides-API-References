---
title: ConstrainedCopy()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คัดลอกช่วงขององค์ประกอบจาก System.Array ที่เริ่มจากแหล่งข้อมูลที่ระบุ
type: docs
weight: 716
url: /th/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

คัดลอกช่วงขององค์ประกอบจาก [System.Array](../) ที่เริ่มจากแหล่งข้อมูลที่ระบุ

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ประเภทขององค์ประกอบในอาร์เรย์ต้นทาง |
| DstType | ประเภทขององค์ประกอบในอาร์เรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงของรายการที่ต้องคัดลอก |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่จะคัดลอก |

## หมายเหตุ

การทำงานดิบชั่วคราวโดยไม่มีการแก้ไขใด ๆ!

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)