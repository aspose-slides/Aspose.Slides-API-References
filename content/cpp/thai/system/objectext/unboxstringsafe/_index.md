---
title: UnboxStringSafe()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึง string จากค่าที่บรรจุในกล่อง
type: docs
weight: 66
url: /th/system/objectext/unboxstringsafe/
---
## ObjectExt::UnboxStringSafe(const SmartPtr\<Object\>\&) เมธอด


Unboxes string from boxed value.

```cpp
static String System::ObjectExt::UnboxStringSafe(const SmartPtr<Object> &obj)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | ค่า string ที่บรรจุอยู่ในกล่อง |

### ค่าที่คืน

หาก **obj** เป็น string ที่บรรจุในกล่อง จะคืนค่าที่ไม่ได้บรรจุ, มิฉะนั้นจะคืนค่า string ว่างเปล่า.

## ดูเพิ่มเติม

* คลาส [String](../../string/)
* คลาส [SmartPtr](../../smartptr/)
* คลาส [Object](../../object/)
* คลาส [ObjectExt](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)