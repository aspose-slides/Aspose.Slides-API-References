---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ API-referencia
description: Megállapítja, hogy az Aspose.Slides törölni fogja-e az összes beágyazott bináris objektumot a bemutató betöltése közben.
type: docs
weight: 352
url: /hu/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metódus


Meghatározza, hogy a(z) [Aspose.Slides](../../) törölni fogja-e az összes beágyazott bináris objektumot a bemutató betöltése közben.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Megjegyzések


A beágyazott bináris objektumok típusai:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) bináris adat [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Írja **bool**. 

Az alapértelmezett **false**. 

A következő példa bemutatja, hogyan tölthető be a bemutató beágyazott bináris objektumok nélkül. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Lásd még

* Osztály [LoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)