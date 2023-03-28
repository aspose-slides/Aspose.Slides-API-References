---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API Reference
description: Returns slide size object. Read-only ISlideSize.
type: docs
weight: 79
url: /cpp/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() method


Returns slide size object. Read-only [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Remarks


The following example shows how to change the slide size in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 The following example shows how to set slide size with respect to content scaling for a PowerPoint [Presentation](../). 
```cpp
// Instantiate a Presentation object that represents a presentation file
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Set the slide size of generated presentations to that of source
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Method SetSize is used for set slide size with scale content to ensure fit
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Method SetSize is used for set slide size with maximize size of content
// Save Presentation to disk
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to specifying custom slide sizes in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 paper size
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlideSize](../../islidesize/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
