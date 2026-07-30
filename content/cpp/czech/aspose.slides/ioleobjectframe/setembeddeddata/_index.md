---
title: SetEmbeddedData()
second_title: Aspose.Slides pro C++ referenci API
description: Nastaví informace o vložených OLE datech.
type: docs
weight: 248
url: /cs/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda


Nastaví informace o vložených OLE datech.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Vložená data [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Poznámky


Tato metoda mění vlastnosti objektu tak, aby odrážely nová data, a nastaví příznak IsObjectLink na false, což naznačuje, že OLE objekt je vložený. 


Následující příklad ukazuje, jak změnit vložená OLE data a jejich typ pro existující objekt [IOleObjectFrame](../) 
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
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IOleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)