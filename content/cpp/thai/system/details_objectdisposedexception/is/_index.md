---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_objectdisposedexception/is/
---
## Details_ObjectDisposedException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Details_ObjectDisposedException::Is(const System::TypeInfo &target) const override
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) structure describing the type to test current object against. |

### Return Value

True if object is of tagged type or its subclass, false otherwise.

## Remarks

ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบคล้ายกับตัวดำเนินการ 'is' ของ C#.

## See Also

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_ObjectDisposedException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)