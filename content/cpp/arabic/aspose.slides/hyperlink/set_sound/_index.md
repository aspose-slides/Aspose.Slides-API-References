---
title: set_Sound()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يمثل الصوت المشغل للارتباط التشعبي. اكتب IAudio.
type: docs
weight: 300
url: /ar/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) طريقة


يمثل الصوت المشغل للارتباط التشعبي. اكتب [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على الارتباط التشعبي للشكل الأول
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صوت الارتباط التشعبي في مصفوفة بايت
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../iaudio/)
* فئة [Hyperlink](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)