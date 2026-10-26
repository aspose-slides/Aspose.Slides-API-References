---
title: SetEmbeddedData()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja az OLE beágyazott adat információkat.
type: docs
weight: 248
url: /hu/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metódus

Beállítja az OLE beágyazott adat információkat.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Beágyazott adat [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Megjegyzések

Ez a metódus módosítja az objektum tulajdonságait, hogy tükrözzék az új adatokat, és az IsObjectLink jelzőt hamisra állítja, jelezve, hogy az OLE objektum beágyazott.

A következő példa bemutatja, hogyan lehet megváltoztatni az OLE beágyazott adatokat és azok típusát egy meglévő [IOleObjectFrame](../) objektumnál 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Osztály [IOleObjectFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)