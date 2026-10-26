---
title: GetEffective()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับข้อมูลการจัดรูปแบบรายการหัวข้อที่มีผลโดยใช้การสืบทอด
type: docs
weight: 248
url: /th/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() เมธอด

รับข้อมูลการจัดรูปแบบรายการหัวข้อที่มีผลโดยใช้การสืบทอด

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```

### ค่าที่ส่งคืน

A [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## หมายเหตุ

ตัวอย่างนี้แสดงการดึงคุณสมบัติของรูปแบบรายการหัวข้อที่มีผล
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* คลาส [BulletFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)