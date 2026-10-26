---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación.
type: docs
weight: 339
url: /es/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() método

Determina si [Aspose.Slides](../../) eliminará todos los objetos binarios incrustados durante la carga de la presentación.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Observaciones

Los tipos de los objetos binarios incrustados:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Leer **bool**. 

El valor predeterminado es **false**. 

El siguiente ejemplo muestra cómo cargar la presentación sin ningún objeto binario incrustado. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Ver también

* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)