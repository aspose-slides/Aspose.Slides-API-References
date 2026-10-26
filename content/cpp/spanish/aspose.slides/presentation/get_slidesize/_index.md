---
title: get_SlideSize()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el objeto de tamaño de diapositiva. Solo lectura ISlideSize.
type: docs
weight: 79
url: /es/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() método


Devuelve el objeto de tamaño de diapositiva. Solo lectura [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Observaciones


El siguiente ejemplo muestra cómo cambiar el tamaño de la diapositiva en un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 El siguiente ejemplo muestra cómo establecer el tamaño de la diapositiva con respecto al escalado del contenido para un PowerPoint [Presentation](../). 
```cpp
// Instanciar un objeto Presentation que representa un archivo de presentación
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Establecer el tamaño de diapositiva de las presentaciones generadas al del origen
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// El método SetSize se usa para establecer el tamaño de diapositiva con contenido escalado para asegurar el ajuste
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// El método SetSize se usa para establecer el tamaño de diapositiva maximizando el tamaño del contenido
// Guardar la presentación en disco
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 El siguiente ejemplo muestra cómo especificar tamaños de diapositiva personalizados en un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Tamaño de papel A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlideSize](../../islidesize/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)