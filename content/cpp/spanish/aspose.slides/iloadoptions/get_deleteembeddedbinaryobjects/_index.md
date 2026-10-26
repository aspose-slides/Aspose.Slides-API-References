---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación.
type: docs
weight: 339
url: /es/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() método

Determina si [Aspose.Slides](../../) eliminará todos los objetos binarios incrustados durante la carga de la presentación.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Observaciones

Los tipos de los objetos binarios incrustados:

* Proyecto VBA [IPresentation::VbaProject](../)
* Datos incrustados de objeto OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) datos binarios [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Lectura **bool**. 

El valor predeterminado es **false**. 

El siguiente ejemplo muestra cómo cargar la presentación sin ningún objeto binario incrustado. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Ver también

* Clase [ILoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)