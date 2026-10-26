---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om Aspose.Slides kommer att ta bort alla inbäddade binära objekt vid presentationsladdning.
type: docs
weight: 352
url: /sv/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metod


Bestämmer om [Aspose.Slides](../../) kommer att ta bort alla inbäddade binära objekt vid presentationsladdning.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Anmärkningar


Typen av de inbäddade binära objekten:

* VBA-projekt [IPresentation::VbaProject](../)
* OLE-objekt inbäddade data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binärdata [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Skriv **bool**. 

Standard är **false**. 

Följande exempel visar hur man laddar presentationen utan några inbäddade binära objekt. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Se även

* Klass [ILoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)