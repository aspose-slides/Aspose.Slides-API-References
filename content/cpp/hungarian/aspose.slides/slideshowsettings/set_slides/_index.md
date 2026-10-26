---
title: set_Slides()
second_title: Aspose.Slides C++ API hivatkozás
description: Diák tartomány
type: docs
weight: 131
url: /hu/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) metódus


[Slides](../../) tartomány

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Megjegyzés



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [SlidesRange](../../slidesrange/)
* Osztály [SlideShowSettings](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)