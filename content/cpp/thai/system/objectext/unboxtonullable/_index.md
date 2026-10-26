---
title: UnboxToNullable()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ถอดกล่องอ็อบเจกต์เป็นประเภท nullable.
type: docs
weight: 79
url: /th/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) เมธอด

ถอดกล่องอ็อบเจกต์เป็นประเภท nullable

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทปลายทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อถอดกล่อง. |
| safe | **bool** | ถ้าเป็น true ให้คืนค่า nullptr เมื่อเกิดความล้มเหลว, มิฉะนั้นให้โยน InvalidCastException. |

### ค่าที่ส่งคืน

ค่าที่ถอดกล่องแบบ nullable (อาจเป็น null).

## ดูเพิ่มเติม

* คลาส [Nullable](../../nullable/)
* คลาส [SmartPtr](../../smartptr/)
* คลาส [Object](../../object/)
* คลาส [ObjectExt](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)