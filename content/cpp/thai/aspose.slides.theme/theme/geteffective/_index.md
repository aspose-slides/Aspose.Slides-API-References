---
title: GetEffective()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับข้อมูลธีมที่มีผลพร้อมการสืบทอดที่นำมาใช้.
type: docs
weight: 53
url: /th/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() เมธอด


รับข้อมูลธีมที่มีผลพร้อมการสืบทอดที่นำมาใช้.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### ค่าที่ส่งคืน

อ็อบเจกต์ [IThemeEffectiveData](../../ithemeeffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการรับคุณสมบัติของธีมที่มีผล 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IThemeEffectiveData](../../ithemeeffectivedata/)
* คลาส [Theme](../)
* เนมสเปซ [Aspose::Slides::Theme](../../)
* ไลบรารี [Aspose.Slides](../../../)