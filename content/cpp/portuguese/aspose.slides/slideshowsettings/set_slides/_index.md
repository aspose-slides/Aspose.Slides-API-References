---
title: set_Slides()
second_title: Aspose.Slides para C++ Referência da API
description: Intervalo de slides
type: docs
weight: 131
url: /pt/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) método


[Slides](../../) intervalo

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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
* Library [Aspose.Slides](../../../)