---
title: GetEffective()
second_title: Aspose.Slides برای C++ مرجع API
description: داده‌های قالب‌بندی پاراگراف مؤثر را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 365
url: /fa/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() متد


داده‌های قالب‌بندی پاراگراف مؤثر را با اعمال وراثت دریافت می‌کند.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### مقدار بازگشتی

یک [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## توضیحات


این مثال نحوه دریافت برخی از خصوصیت‌های مؤثر قالب پاراگراف را نشان می‌دهد. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* کلاس [ParagraphFormat](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)