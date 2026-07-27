---
title: get_Masters()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una lista de todas las diapositivas maestras que están definidas en la presentación. Solo lectura IMasterSlideCollection.
type: docs
weight: 118
url: /es/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() método

Devuelve una lista de todas las diapositivas maestras que están definidas en la presentación. Solo lectura [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Observaciones

Los siguientes ejemplos muestran cómo agregar [Images](../../images/) a la diapositiva maestra [Slides](../../) de PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 Los siguientes ejemplos muestran cómo cambiar el color de fondo de la diapositiva maestra de PowerPoint [Presentation](../). 
```cpp
// Instanciar la clase Presentation que representa el archivo de presentación
auto pres = System::MakeObject<Presentation>();

// Establecer el color de fondo de la diapositiva maestra ISlide a verde bosque
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Guardar la presentación en disco
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 Los siguientes ejemplos muestran cómo agregar una disposición de diapositiva a PowerPoint [Presentation](../). 
```cpp
// Instanciar la clase Presentation que representa el archivo de presentación
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Intentar buscar por tipo de diapositiva de diseño
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // La situación cuando una presentación no contiene algún tipo de diseños.
    // El archivo de presentación solo contiene tipos de diseños en blanco y personalizados.
    // Pero las diapositivas de diseño con tipos personalizados tienen nombres de diapositiva diferentes,
    // como "Title", "Title and Content", etc. Y es posible usar estos
    // nombres para la selección de diapositivas de diseño.
    // También es posible usar el conjunto de tipos de forma de marcador de posición. Por ejemplo,
    // La diapositiva de título solo debe tener el tipo de marcador de posición Title, etc.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// Añadiendo una diapositiva vacía con la diapositiva de diseño agregada
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Guardar la presentación
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)