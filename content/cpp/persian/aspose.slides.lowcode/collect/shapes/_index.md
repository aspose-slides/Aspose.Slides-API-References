---
title: Shapes()
second_title: Aspose.Slides برای مرجع API C++
description: تمام نمونه‌های Shape را در Presentation جمع‌آوری می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) متد

تمام نمونه‌های [Shape](../../../aspose.slides/shape/) را در [Presentation](../../../aspose.slides/presentation/) جمع‌آوری می‌کند.

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای جمع‌آوری اشکال |

### مقدار برگشتی

مجموعه‌ای از تمام اشکالی که در ارائه موجود هستند

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // اگر شکل AutoShape باشد، یک حاشیه مشکی ثابت اضافه کنید
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [Shape](../../../aspose.slides/shape/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [Collect](../)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)