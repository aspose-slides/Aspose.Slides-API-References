---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.
type: docs
weight: 339
url: /hu/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metódus

Meghatározza, hogy a(z) [Aspose.Slides](../../) törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Megjegyzések

A beágyazott bináris objektumok típusai:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Olvasás **bool**.

Az alapértelmezett **false**.

Az alábbi példa bemutatja, hogyan lehet betölteni a prezentációt beágyazott bináris objektumok nélkül.
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