---
title: get_MasterTheme()
second_title: Aspose.Slides لمرجع API للغة C++
description: "يرجع السمة الرئيسية. للقراءة فقط Theme::IMasterTheme."
type: docs
weight: 404
url: /ar/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() طريقة


يرجع السمة الرئيسية. للقراءة فقط [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## ملاحظات


توضح الأمثلة التالية كيفية تغيير تأثير السمة عن طريق تعديل أجزاء من عناصر PowerPoint [Presentation](../). 
```cpp
// إنشاء كائن عرض تقديمي يمثل ملف عرض تقديمي
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* فئة [Presentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)