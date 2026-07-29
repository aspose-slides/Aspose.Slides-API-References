---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om Aspose.Slides ska ta bort alla inbäddade binära objekt vid presentationens laddning.
type: docs
weight: 352
url: /sv/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metod

Bestämmer om [Aspose.Slides](../../) kommer att ta bort alla inbäddade binära objekt under presentationens laddning.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Anmärkningar

Typerna av de inbäddade binära objekten:

* VBA Projekt [IPresentation::VbaProject](../)
* OLE-objekt inbäddad data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binär data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Skriv **bool**.

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