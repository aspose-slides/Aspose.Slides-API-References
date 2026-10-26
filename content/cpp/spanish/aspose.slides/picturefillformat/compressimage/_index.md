---
title: CompressImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.
type: docs
weight: 443
url: /es/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) method

Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Si es true, el método eliminará las áreas recortadas de la imagen, reduciendo potencialmente aún más su tamaño. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | La resolución objetivo para la compresión, especificada como un valor del enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Valor devuelto

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve ****true****

## Observaciones

Este método cambia el tamaño y la resolución de la imagen de manera similar a la función "Picture Format -> Compress Pictures" de PowerPoint.

si la imagen fue redimensionada o recortada, de lo contrario ****false****

.

El siguiente ejemplo demuestra cómo usar el método **CompressImage** para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando áreas recortadas: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Comprime la imagen con una resolución objetivo de 150 DPI (resolución web) y elimina las áreas recortadas
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) method

Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Si es true, el método eliminará las áreas recortadas de la imagen, reduciendo potencialmente aún más su tamaño. |
| resolution | **float** | La resolución objetivo en DPI. Este valor debe ser positivo y define cómo se redimensionará la imagen. |

### Valor devuelto

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve ****true****

## Observaciones

Este método cambia el tamaño y la resolución de la imagen de manera similar a la función "Picture Format -> Compress Pictures" de PowerPoint.

si la imagen fue redimensionada o recortada, de lo contrario ****false****

.

El siguiente ejemplo demuestra cómo usar el método **CompressImage** para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando áreas recortadas: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Comprime la imagen con una resolución objetivo de 150 DPI (resolución web) y elimina las áreas recortadas
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Resolución web
```

## Véase también

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)