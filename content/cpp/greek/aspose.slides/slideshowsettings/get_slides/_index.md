---
title: get_Slides()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Εύρος διαφανειών
type: docs
weight: 118
url: /el/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const μέθοδος


[Slides](../../) εύρος

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [SlidesRange](../../slidesrange/)
* Κλάση [SlideShowSettings](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)