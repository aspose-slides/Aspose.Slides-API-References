---
title: WriteAsEmf()
second_title: Referencia de API de Aspose.Slides para C++
description: Guarda el contenido de la diapositiva como un archivo EMF.
type: docs
weight: 170
url: /es/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) método

Guarda el contenido de la diapositiva como un archivo EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de destino |
## Observaciones

El siguiente ejemplo de código muestra cómo convertir la primera diapositiva de una presentación de PowerPoint en un metarchivo. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Guarda la primera diapositiva como un metarchivo
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [Slide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)