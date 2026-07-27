---
title: WriteAsEmf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Guarda la imagen SVG como un archivo EMF.
type: docs
weight: 53
url: /es/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) método

Guarda la imagen SVG como un archivo EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de destino |
## Observaciones

El siguiente ejemplo muestra cómo guardar la imagen SVG en un archivo metafile. 
```cpp
// Crea la nueva imagen SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Guarda la imagen SVG como un metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Este ejemplo muestra cómo agregar la imagen SVG como un metafile a la colección de imágenes de la presentación. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Crea la nueva imagen SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Guarda la imagen SVG como un metafile
svgImage->WriteAsEmf(memStream);
// Agrega el metafile a la colección de imágenes
pres->get_Images()->AddImage(memStream->ToArray());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [ISvgImage](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)