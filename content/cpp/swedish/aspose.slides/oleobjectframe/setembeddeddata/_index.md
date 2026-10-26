---
title: SetEmbeddedData()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in information om OLE inbäddade data.
type: docs
weight: 248
url: /sv/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metod

Ställer in information om OLE-inbäddade data.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Inbäddade data [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Anmärkningar

Denna metod ändrar objektets egenskaper för att återspegla de nya data och sätter flaggan IsObjectLink till false, vilket indikerar att OLE-objektet är inbäddat. 



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
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [OleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)