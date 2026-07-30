---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides pro C++ API Referenci
description: Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty.
type: docs
weight: 352
url: /cs/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metoda


Určuje, zda [Aspose.Slides](../../) při načítání prezentace smaže všechny vložené binární objekty.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Poznámky


Typy vložených binárních objektů:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binární data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Zapište **bool**. 

Výchozí hodnota je **false**. 

Následující příklad ukazuje, jak načíst prezentaci bez vložených binárních objektů. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Viz také

* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)