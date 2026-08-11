---
title: FindAndReplaceText()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بالبحث واستبدال النص في العرض التقديمي بالتنسيق المحدد
type: docs
weight: 40
url: /ar/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method


يقوم بالبحث واستبدال النص في العرض التقديمي بالتنسيق المحدد

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### المعطيات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | العرض التقديمي المفحوص. |
| withMasters | **bool** | يحدد ما إذا كان يجب فحص الشرائح الرئيسة. |
| find | [System::String](../../../system/string/) | قيمة السلسلة للبحث. |
| replace | [System::String](../../../system/string/) | قيمة السلسلة للاستبدال. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | التنسيق لاستبدال جزء النص. إذا كان null فسيُستخدم تنسيق الحرف الأول من السلسلة التي تم العثور عليها |
## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```




## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPresentation](../../../aspose.slides/ipresentation/)
* فئة [String](../../../system/string/)
* فئة [PortionFormat](../../../aspose.slides/portionformat/)
* فئة [SlideUtil](../)
* مساحة أسماء [Aspose::Slides::Util](../../)
* مكتبة [Aspose.Slides](../../../)