---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.
type: docs
weight: 339
url: /hu/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() metódus


Meghatározza, hogy a [Aspose.Slides](../../) törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Megjegyzések


A beágyazott bináris objektumok típusai:

* VBA Projekt [IPresentation::VbaProject](../)
* OLE Objektum beágyazott adatok [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) bináris adatok [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Olvasás **bool**. 

Az alapértelmezett **false**. 

A következő példa azt mutatja, hogyan lehet betölteni a bemutatót beágyazott bináris objektumok nélkül. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Lásd még

* Osztály [ILoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)