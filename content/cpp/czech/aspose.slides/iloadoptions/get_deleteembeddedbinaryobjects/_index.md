---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides pro C++ reference API
description: Určuje, zda Aspose.Slides při načítání prezentace odstraní všechny vložené binární objekty.
type: docs
weight: 339
url: /cs/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() method


Určuje, zda [Aspose.Slides](../../) odstraní všechny vložené binární objekty při načítání prezentace.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Poznámky


Typy vložených binárních objektů:

* Projekt VBA [IPresentation::VbaProject](../)
* data vloženého objektu OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binární data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Vrací **bool**. 

Výchozí hodnota je **false**. 

Následující příklad ukazuje, jak načíst prezentaci bez jakýchkoli vložených binárních objektů. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Viz také

* Třída [ILoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)