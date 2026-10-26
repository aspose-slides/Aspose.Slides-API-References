---
title: get_Images()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la colección de todas las imágenes en la presentación. Solo lectura IImageCollection.
type: docs
weight: 209
url: /es/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() method


Devuelve la colección de todas las imágenes en la presentación. Solo lectura [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Observaciones


Los siguientes ejemplos muestran cómo agregar una imagen como BLOB en PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// crea una nueva presentación a la que se añadirá la imagen.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Añadamos la imagen a la presentación - elegimos el comportamiento KeepLocked porque vamos
// NO tener la intención de acceder al archivo "largeImage.png".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Guarda la presentación. Mientras se genera una presentación grande, el consumo de memoria
// permanece bajo durante el ciclo de vida del objeto pres
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Los siguientes ejemplos agregan un hipervínculo a una imagen en PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Agrega la imagen a la presentación
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Crea un marco de imagen en la diapositiva 1 basado en la imagen añadida previamente
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImageCollection](../../iimagecollection/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)