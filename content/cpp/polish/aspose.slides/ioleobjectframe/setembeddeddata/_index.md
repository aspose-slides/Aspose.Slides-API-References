---
title: SetEmbeddedData()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ustawia informacje o wbudowanych danych OLE.
type: docs
weight: 248
url: /pl/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda

Ustawia informacje o wbudowanych danych OLE.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Wbudowane dane [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Uwagi

Ta metoda zmienia właściwości obiektu, aby odzwierciedlić nowe dane i ustawia flagę IsObjectLink na false, wskazując, że obiekt OLE jest osadzony.

Poniższy przykład pokazuje, jak zmienić wbudowane dane OLE i ich typ dla istniejącego obiektu [IOleObjectFrame](../) 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasa [IOleObjectFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)