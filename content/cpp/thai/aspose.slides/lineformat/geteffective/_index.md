---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับข้อมูลการจัดรูปแบบเส้นที่มีผลจริงพร้อมการสืบทอดที่นำมาใช้.
type: docs
weight: 417
url: /th/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() เมธอด


รับข้อมูลการจัดรูปแบบเส้นที่มีผลจริงพร้อมการสืบทอดที่นำมาใช้.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### ค่าที่ส่งกลับ

หนึ่ง [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการดึงคุณสมบัติรูปแบบเส้นที่มีผลจริงของรูป. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* คลาส [LineFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)