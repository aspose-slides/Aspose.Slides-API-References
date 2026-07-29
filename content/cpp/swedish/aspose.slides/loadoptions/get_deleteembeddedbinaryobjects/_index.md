---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om Aspose.Slides kommer att ta bort alla inbäddade binära objekt när presentationen laddas.
type: docs
weight: 339
url: /sv/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metod


Avgör om [Aspose.Slides](../../) kommer att ta bort alla inbäddade binära objekt när presentationen laddas.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Anmärkningar


Typerna av de inbäddade binära objekten:

* VBA Projekt [IPresentation::VbaProject](../)
* OLE Object inbäddade data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binära data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Läs **bool**. 

Standard är **false**. 

Följande exempel visar hur man laddar presentationen utan några inbäddade binära objekt. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Se också

* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)