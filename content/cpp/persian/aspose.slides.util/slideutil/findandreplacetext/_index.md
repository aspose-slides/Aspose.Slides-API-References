---
title: FindAndReplaceText()
second_title: مرجع API Aspose.Slides برای C++
description: متن را در ارائه جستجو کرده و با قالب داده‌شده جایگزین می‌کند
type: docs
weight: 40
url: /fa/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) متد


متن را در ارائه جستجو و جایگزین می‌کند با قالب داده شده

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | ارائه اسکن‌شده. |
| withMasters | **bool** | تعیین می‌کند آیا اسلایدهای مستر باید اسکن شوند. |
| find | [System::String](../../../system/string/) | مقدار رشته‌ای برای جستجو. |
| replace | [System::String](../../../system/string/) | مقدار رشته‌ای برای جایگزینی. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | قالب برای جایگزینی بخش متن. اگر null باشد قالب اولین کاراکتر رشتهٔ پیدا شده استفاده می‌شود |
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




## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPresentation](../../../aspose.slides/ipresentation/)
* کلاس [String](../../../system/string/)
* کلاس [PortionFormat](../../../aspose.slides/portionformat/)
* کلاس [SlideUtil](../)
* فضای نام [Aspose::Slides::Util](../../)
* کتابخانه [Aspose.Slides](../../../)