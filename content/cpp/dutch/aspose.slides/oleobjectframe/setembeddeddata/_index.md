---
title: SetEmbeddedData()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt informatie in over OLE-ingesloten gegevens.
type: docs
weight: 248
url: /nl/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) methode

Stelt informatie in over OLE-ingesloten gegevens.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Ingesloten gegevens [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Opmerkingen

Deze methode wijzigt de eigenschappen van het object om de nieuwe gegevens weer te geven en stelt de IsObjectLink-vlag in op false, wat aangeeft dat het OLE-object is ingesloten. 

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
* Klasse [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasse [OleObjectFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)