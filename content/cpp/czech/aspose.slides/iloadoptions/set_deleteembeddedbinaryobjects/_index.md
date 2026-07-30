---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty.
type: docs
weight: 352
url: /cs/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) method


Určuje, zda [Aspose.Slides](../../) při načítání prezentace smaže všechny vložené binární objekty.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Poznámky


Typy vložených binárních objektů:

* projekt VBA [IPresentation::VbaProject](../)
* vložená data OLE objektu [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binární data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Zapište **bool**. 

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