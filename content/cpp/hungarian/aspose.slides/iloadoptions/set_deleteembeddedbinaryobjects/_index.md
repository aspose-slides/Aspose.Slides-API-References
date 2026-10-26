---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ API referenciája
description: Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a bemutató betöltése során.
type: docs
weight: 352
url: /hu/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metódus

Meghatározza, hogy a [Aspose.Slides](../../) törli-e az összes beágyazott bináris objektumot a bemutató betöltése során.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Megjegyzések

A beágyazott bináris objektumok típusai:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) bináris adat [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Írja **bool**.

Az alapértelmezett érték **false**.

Az alábbi példa bemutatja, hogyan lehet betölteni a bemutatót beágyazott bináris objektumok nélkül.
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