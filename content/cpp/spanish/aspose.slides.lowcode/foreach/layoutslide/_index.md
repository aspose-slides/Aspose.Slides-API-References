---
title: LayoutSlide()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Itera cada ForEach::LayoutSlide en la Presentación."
type: docs
weight: 27
url: /es/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) method

Itera cada [ForEach::LayoutSlide](./) en el [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar diapositivas de diseño |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Callback que será invocado para cada diapositiva de diseño |

## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [ForEach](../)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)