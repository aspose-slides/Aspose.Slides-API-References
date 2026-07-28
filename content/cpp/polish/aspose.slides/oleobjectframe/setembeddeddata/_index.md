---
title: SetEmbeddedData()
second_title: Aspose.Slides dla C++ - Referencja API
description: Ustawia informacje o osadzonych danych OLE.
type: docs
weight: 248
url: /pl/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Ustawia informacje o osadzonych danych OLE.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Dane osadzone [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Uwagi


Ta metoda zmienia właściwości obiektu, aby odzwierciedlić nowe dane i ustawia flagę IsObjectLink na false, wskazując, że obiekt OLE jest osadzony. 



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasa [OleObjectFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)