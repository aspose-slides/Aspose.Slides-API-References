---
title: get_InkEffect()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "รับค่าชนิดของเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดสไตล์การแสดงผลของเส้นหมึก ค่าจะถูกแยกวิเคราะห์จากคุณสมบัติของแปรง \"inkEffects\" หากไม่มีเอฟเฟกต์ที่รับรู้ได้ระบุไว้ จะคืนค่า InkEffectType::NotDefined"
type: docs
weight: 53
url: /th/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() เมธอด

รับค่าชนิดของเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดสไตล์การแสดงผลของเส้นหมึก ค่าเหล่านี้จะถูกแยกวิเคราะห์จากคุณสมบัติของแปรง "inkEffects" หากไม่มีเอฟเฟกต์ที่รับรู้ได้ระบุไว้ จะคืนค่า [InkEffectType::NotDefined](../../inkeffecttype/).

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## ดูเพิ่มเติม

* Enum [InkEffectType](../../inkeffecttype/)
* Class [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)