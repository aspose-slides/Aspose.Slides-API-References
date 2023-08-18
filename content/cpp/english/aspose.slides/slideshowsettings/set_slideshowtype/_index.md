---
title: set_SlideShowType()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the slide show type. Represented by the following SlideShowType ancestors: BrowsedAtKiosk, PresentedBySpeaker and BrowsedByIndividual"
type: docs
weight: 14
url: /aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) method


Sets the slide show type. Represented by the following [SlideShowType](../../slideshowtype/) ancestors: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) and [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>();

// to set "Browsed at a kiosk (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// to set "Browsed by individual (window)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// to set "Presented by a speaker (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SlideShowType](../../slideshowtype/)
* Class [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)