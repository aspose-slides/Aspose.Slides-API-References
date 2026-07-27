---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación.
type: docs
weight: 352
url: /es/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) método


Determina si [Aspose.Slides](../../) eliminará todos los objetos binarios incrustados al cargar la presentación.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Observaciones


Los tipos de los objetos binarios incrustados:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Escriba **bool**. 

El valor predeterminado es **false**. 

El siguiente ejemplo muestra cómo cargar la presentación sin ningún objeto binario incrustado. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Ver también

* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)