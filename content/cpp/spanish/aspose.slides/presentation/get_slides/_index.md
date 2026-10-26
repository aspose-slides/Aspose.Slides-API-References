---
title: get_Slides()
second_title: Referencia API de Aspose.Slides para C++
description: Devuelve una lista de todas las diapositivas que están definidas en la presentación. Solo lectura ISlideCollection.
type: docs
weight: 53
url: /es/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() method

Devuelve una lista de todas las diapositivas que están definidas en la presentación. Solo lectura [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Observaciones

El siguiente ejemplo muestra cómo establecer el color de fondo de las diapositivas de PowerPoint [Presentation](../).
```cpp
// Instanciar la clase Presentation que representa el archivo de presentación
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Establecer el color de fondo del primer ISlide a Azul
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
El siguiente ejemplo muestra cómo establecer la imagen de fondo de las diapositivas de PowerPoint [Presentation](../).
```cpp
// Instanciar la clase Presentation que representa el archivo de presentación
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Establecer el fondo con Imagen
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Establecer la imagen
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Agregar la imagen a la colección de imágenes de la presentación
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Escribir la presentación en disco
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
El siguiente ejemplo muestra cómo añadir una transición de diapositiva [Presentation](../).
```cpp
// Instanciar la clase Presentation para cargar el archivo de presentación origen
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Aplicar transición tipo círculo en la diapositiva 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Aplicar transición tipo peine en la diapositiva 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Escribir la presentación en disco
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
El siguiente ejemplo muestra cómo añadir una transición de diapositiva avanzada.
```cpp
// Instanciar la clase Presentation que representa un archivo de presentación
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Aplicar transición de tipo círculo en la diapositiva 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Establecer el tiempo de transición de 3 segundos
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Aplicar transición de tipo peine en la diapositiva 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Establecer el tiempo de transición de 5 segundos
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Aplicar transición de tipo zoom en la diapositiva 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Establecer el tiempo de transición de 7 segundos
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Escribir la presentación en disco
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlideCollection](../../islidecollection/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)