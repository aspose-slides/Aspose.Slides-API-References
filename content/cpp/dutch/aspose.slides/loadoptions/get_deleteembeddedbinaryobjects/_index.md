---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.
type: docs
weight: 339
url: /nl/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() methode


Bepaalt of [Aspose.Slides](../../) alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Opmerkingen


De types van de ingebedde binaire objecten:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object ingesloten gegevens [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binaire gegevens [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Lezen **bool**. 

Standaard is **false**. 

Het volgende voorbeeld toont hoe de presentatie te laden zonder enige ingebedde binaire objecten. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Zie ook

* Klasse [LoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)