---
title: get_Slides()
second_title: Referência da API Aspose.Slides para C++
description: Intervalo de slides
type: docs
weight: 118
url: /pt/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const método


[Slides](../../) intervalo

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlidesRange](../../slidesrange/)
* Classe [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)