---
title: get_Masters()
second_title: Aspose.Slides for C++ API Reference
description: Returns a list of all master slides that are defined in the presentation. Read-only IMasterSlideCollection.
type: docs
weight: 118
url: /aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() method


Returns a list of all master slides that are defined in the presentation. Read-only [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Remarks


The following examples shows how to adding [Images](../../images/) to Master [Slides](../../) of PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 The following examples shows how to change the background color of the master slide of PowerPoint [Presentation](../). 
```cpp
// Instantiate the Presentation class that represents the presentation file
auto pres = System::MakeObject<Presentation>();

// Set the background color of the Master ISlide to Forest Green
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Write the presentation to disk
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 The following examples shows how to add slide layout to PowerPoint [Presentation](../). 
```cpp
// Instantiate Presentation class that represents the presentation file
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Try to search by layout slide type
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // The situation when a presentation doesn't contain some type of layouts.
    // presentation File only contains Blank and Custom layout types.
    // But layout slides with Custom types has different slide names,
    // like "Title", "Title and Content", etc. And it is possible to use these
    // names for layout slide selection.
    // Also it is possible to use the set of placeholder shape types. For example,
    // Title slide should have only Title pleceholder type, etc.
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

// Adding empty slide with added layout slide
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Save presentation
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)