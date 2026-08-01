---
title: SetEmbeddedData()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt informatie over OLE-embedded data in.
type: docs
weight: 248
url: /nl/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Stelt informatie over OLE embedded data in.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Ingebedde data [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Opmerkingen


Deze methode wijzigt de eigenschappen van het object om de nieuwe data weer te geven en zet de IsObjectLink-vlag op false, wat aangeeft dat het OLE-object is ingesloten. 


Het volgende voorbeeld toont hoe OLE embedded data en het type ervan te wijzigen voor een bestaand [IOleObjectFrame](../) object 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IOleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)