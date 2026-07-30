---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda Aspose.Slides smaže všechny vložené binární objekty při načítání prezentace.
type: docs
weight: 339
url: /cs/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metoda

Určuje, zda [Aspose.Slides](../../) smaže všechny vložené binární objekty při načítání prezentace.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Poznámky

Typy vložených binárních objektů:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binární data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Čte se **bool**. 

Výchozí hodnota je **false**. 

Následující příklad ukazuje, jak načíst prezentaci bez jakýchkoli vložených binárních objektů. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Viz také

* Třída [LoadOptions](../)
* Prostor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)