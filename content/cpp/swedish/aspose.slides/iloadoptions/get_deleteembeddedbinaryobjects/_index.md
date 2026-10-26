---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om Aspose.Slides kommer att ta bort alla inbäddade binära objekt vid presentationens inläsning.
type: docs
weight: 339
url: /sv/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() metod


Bestämmer om [Aspose.Slides](../../) kommer att ta bort alla inbäddade binära objekt när presentationen läses in.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Anmärkningar


Typerna av de inbäddade binära objekten:

* VBA-projekt [IPresentation::VbaProject](../)
* OLE-objekt inbäddade data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binär data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Läs **bool**. 

Standard är **false**. 

Följande exempel visar hur du laddar presentationen utan några inbäddade binära objekt. 
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