---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ - referenční příručka API
description: Nastavuje informace o vložených OLE datech.
type: docs
weight: 248
url: /cs/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda

Nastavuje informace o vložených OLE datech.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Vložená data [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Poznámky

Tato metoda mění vlastnosti objektu tak, aby odrážely nová data, a nastavuje příznak IsObjectLink na false, což naznačuje, že OLE objekt je vložen. 



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Třída [OleObjectFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)