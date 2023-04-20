---
title: get_Slides()
second_title: Aspose.Slides for C++ API Reference
description: Returns a list of all slides that are defined in the presentation. Read-only ISlideCollection.
type: docs
weight: 53
url: /cpp/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() method


Returns a list of all slides that are defined in the presentation. Read-only [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Remarks


The following example shows how to set slides' background color of PowerPoint [Presentation](../). 
```cpp
// Instantiate the Presentation class that represents the presentation file
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to set slides' background image of PowerPoint [Presentation](../). 
```cpp
// Instantiate the Presentation class that represents the presentation file
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Set the background with Image
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(Aspose::Slides::PictureFillMode::Stretch);
// Set the picture
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Add image to presentation's images collection
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Write the presentation to disk
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to add slide transition [Presentation](../). 
```cpp
// Instantiate Presentation class to load the source presentation file
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Apply circle type transition on slide 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Apply comb type transition on slide 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Write the presentation to disk
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to add advanced slide Transition. 
```cpp
// Instantiate Presentation class that represents a presentation file
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Apply circle type transition on slide 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Set the transition time of 3 seconds
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Apply comb type transition on slide 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Set the transition time of 5 seconds
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Apply zoom type transition on slide 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Set the transition time of 7 seconds
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Write the presentation to disk
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlideCollection](../../islidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)