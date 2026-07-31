---
title: get_IncludeHiddenSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan atau mengatur apakah slide tersembunyi harus disertakan.
type: docs
weight: 27
url: /id/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const metode


Mendapatkan atau mengatur apakah slide tersembunyi harus disertakan.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Lihat Juga

* Kelas [PresentationAnimationsGenerator](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)