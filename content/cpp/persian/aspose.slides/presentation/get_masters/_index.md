---
title: get_Masters()
second_title: Aspose.Slides برای C++ مرجع API
description: فهرستی از تمام اسلایدهای اصلی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی IMasterSlideCollection.
type: docs
weight: 118
url: /fa/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() متد

لیست تمام اسلایدهای اصلی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط خواندنی [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## یادداشت‌ها

مثال‌های زیر نشان می‌دهد چگونه [Images](../../images/) را به Master [Slides](../../) در PowerPoint [Presentation](../) اضافه کرد.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
مثال‌های زیر نشان می‌دهد چگونه رنگ پس‌زمینه اسلاید اصلی PowerPoint [Presentation](../) را تغییر داد.
```cpp
// نمونه‌سازی کلاس Presentation که فایل ارائه را نمایندگی می‌کند
auto pres = System::MakeObject<Presentation>();

// تنظیم رنگ پس‌زمینه Master ISlide به سبز جنگلی
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// نوشتن ارائه به دیسک
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
مثال‌های زیر نشان می‌دهد چگونه چیدمان اسلاید را به PowerPoint [Presentation](../) اضافه کرد.
```cpp
// نمونه‌سازی کلاس Presentation که فایل ارائه را نمایندگی می‌کند
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// سعی در جستجو بر اساس نوع اسلاید طرح‌بندی
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // موقعیتی که در آن ارائه برخی انواع طرح‌بندی‌ها را شامل نمی‌شود.
    // فایل ارائه فقط شامل انواع طرح‌بندی Blank و Custom است.
    // اما اسلایدهای طرح‌بندی با نوع Custom نام‌های متفاوتی دارند،
    // مانند "Title"، "Title and Content"، و غیره. و امکان استفاده از این
    // نام‌ها برای انتخاب اسلاید طرح‌بندی وجود دارد.
    // همچنین می‌توان مجموعه‌ای از انواع شکل‌های جای‌دار را استفاده کرد. برای مثال،
    // اسلاید عنوان باید فقط نوع جای‌دار Title را داشته باشد، و غیره.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// افزودن اسلاید خالی با اسلاید طرح‌بندی اضافه‌شده
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// ذخیره ارائه
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)