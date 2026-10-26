---
title: get_Slides()
second_title: Riferimento API di Aspose.Slides per C++
description: Intervallo di diapositive
type: docs
weight: 118
url: /it/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const metodo


[Slides](../../) intervallo

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlidesRange](../../slidesrange/)
* Classe [SlideShowSettings](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)