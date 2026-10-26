---
title: get_Masters()
second_title: Aspose.Slides لـ C++ مرجع API
description: إرجاع قائمة بجميع الشرائح الرئيسية التي تم تعريفها في العرض التقديمي. القراءة فقط IMasterSlideCollection.
type: docs
weight: 118
url: /ar/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() طريقة

إرجاع قائمة بجميع الشرائح الرئيسية التي تم تعريفها في العرض التقديمي. القراءة فقط [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## ملاحظات

تظهر الأمثلة التالية كيفية إضافة [Images](../../images/) إلى Master [Slides](../../) من PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
تظهر الأمثلة التالية كيفية تغيير لون الخلفية للماستر سلايد في PowerPoint [Presentation](../).
```cpp
// إنشاء كائن من فئة Presentation التي تمثل ملف العرض التقديمي
auto pres = System::MakeObject<Presentation>();

// تعيين لون خلفية Master ISlide إلى اللون الأخضر الغابي
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// كتابة العرض التقديمي إلى القرص
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
تظهر الأمثلة التالية كيفية إضافة تخطيط الشريحة إلى PowerPoint [Presentation](../).
```cpp
// إنشاء كائن من فئة Presentation التي تمثل ملف العرض التقديمي
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// محاولة البحث حسب نوع شريحة التخطيط
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // الحالة عندما لا يحتوي العرض التقديمي على بعض أنواع التخطيطات.
    // ملف العرض التقديمي يحتوي فقط على نوعي التخطيط Blank و Custom.
    // لكن شرائح التخطيط ذات الأنواع Custom لديها أسماء شرائح مختلفة،
    // مثل "Title"، "Title and Content"، إلخ. ويمكن استخدام هذه
    // الأسماء لاختيار شرائح التخطيط.
    // كما يمكن استخدام مجموعة أنواع أشكال العنصر النائب. على سبيل المثال،
    // يجب أن تحتوي شريحة العنوان على نوع العنصر النائب Title فقط، إلخ.
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

// إضافة شريحة فارغة مع شريحة التخطيط المضافة
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// حفظ العرض التقديمي
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صنف [IMasterSlideCollection](../../imasterslidecollection/)
* صنف [Presentation](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)