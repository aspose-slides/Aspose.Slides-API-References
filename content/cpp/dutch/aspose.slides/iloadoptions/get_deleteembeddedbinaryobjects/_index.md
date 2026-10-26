---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of Aspose.Slides alle ingesloten binaire objecten zal verwijderen tijdens het laden van de presentatie.
type: docs
weight: 339
url: /nl/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() methode


Bepaalt of [Aspose.Slides](../../) alle ingesloten binaire objecten zal verwijderen tijdens het laden van de presentatie.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Opmerkingen


De types van de ingesloten binaire objecten:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object ingesloten gegevens [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binaire gegevens [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Lezen **bool**. 

Standaard is **false**. 

Het volgende voorbeeld laat zien hoe de presentatie kan worden geladen zonder enige ingesloten binaire objecten. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Zie ook

* Klasse [ILoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)