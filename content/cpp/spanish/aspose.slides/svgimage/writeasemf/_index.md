---
title: WriteAsEmf()
second_title: Referencia de API de Aspose.Slides para C++
description: Guarda la imagen SVG como un archivo EMF.
type: docs
weight: 66
url: /es/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) método

Guarda la imagen SVG como un archivo EMF.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de destino |
## Observaciones

El siguiente ejemplo demuestra cómo guardar la imagen SVG en un metarchivo. 
```cpp
// Crea la nueva imagen SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Guarda la imagen SVG como un metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Este ejemplo demuestra cómo agregar la imagen SVG como metarchivo a la colección de imágenes de la presentación. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Crea la nueva imagen SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Guarda la imagen SVG como un metarchivo
svgImage->WriteAsEmf(memStream);
// Agrega el metarchivo a la colección de imágenes
pres->get_Images()->AddImage(memStream->ToArray());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [SvgImage](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)