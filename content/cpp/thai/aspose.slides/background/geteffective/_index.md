---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับข้อมูลพื้นหลังที่มีผลพร้อมการประยุกต์ใช้การสืบทอด.
type: docs
weight: 118
url: /th/aspose.slides/background/geteffective/
---
## Background::GetEffective() เมธอด


รับข้อมูลพื้นหลังที่มีผลโดยใช้การสืบทอดที่ได้ถูกนำมาใช้.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### ค่าที่ส่งกลับ

หนึ่ง [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการดึงคุณสมบัติเพื้นหลังที่เป็นผล 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Class [Background](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)