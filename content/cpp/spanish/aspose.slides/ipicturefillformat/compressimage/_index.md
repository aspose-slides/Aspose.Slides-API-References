---
title: CompressImage()
second_title: Referencia API de Aspose.Slides para C++
description: Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.
type: docs
weight: 443
url: /es/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) método


Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Si es **true**, el método eliminará las áreas recortadas de la imagen, lo que podrá reducir aún más su tamaño. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | La resolución objetivo para la compresión, especificada como un valor del enumerado [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Valor devuelto

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve ****true****

## Comentarios


Este método cambia el tamaño y la resolución de la imagen de forma similar a la función de PowerPoint "Picture Format -> Compress Pictures".

si la imagen se redimensionó o recortó, de lo contrario ****false****

. 


El siguiente ejemplo muestra cómo usar el método **CompressImage** para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando las áreas recortadas: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Comprime la imagen con una resolución objetivo de 150 DPI (resolución web) y elimina las áreas recortadas
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) método


Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Si es **true**, el método eliminará las áreas recortadas de la imagen, lo que podrá reducir aún más su tamaño. |
| resolution | **float** | La resolución objetivo en DPI. Este valor debe ser positivo y define cómo se redimensionará la imagen. |

### Valor devuelto

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve ****true****

## Comentarios


Este método cambia el tamaño y la resolución de la imagen de forma similar a la función de PowerPoint "Picture Format -> Compress Pictures".

si la imagen se redimensionó o recortó, de lo contrario ****false****

. 


El siguiente ejemplo muestra cómo usar el método **CompressImage** para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando las áreas recortadas: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Comprime la imagen con una resolución objetivo de 150 DPI (resolución web) y elimina las áreas recortadas
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Resolución web
```

## Ver también

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)