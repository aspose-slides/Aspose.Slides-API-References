---
title: get_SlideShowType()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the slide show type. Represented by the following SlideShowType ancestors: BrowsedAtKiosk, PresentedBySpeaker and BrowsedByIndividual"
type: docs
weight: 1
url: /aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() method


Gets the slide show type. Represented by the following [SlideShowType](../../slideshowtype/) ancestors: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) and [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
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