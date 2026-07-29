---
title: SetEmbeddedData()
second_title: Aspose.Slides för C++ API-referens
description: Anger information om OLE inbäddade data.
type: docs
weight: 248
url: /sv/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metod

Anger information om OLE inbäddade data.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Inbäddade data [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Anmärkningar

Denna metod ändrar objektets egenskaper för att återspegla de nya data och sätter IsObjectLink-flaggan till false, vilket indikerar att OLE-objektet är inbäddat.

Följande exempel visar hur man ändrar OLE inbäddade data och dess typ för ett befintligt [IOleObjectFrame](../)-objekt.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klass [IOleObjectFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)