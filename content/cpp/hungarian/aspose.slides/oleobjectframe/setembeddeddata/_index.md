---
title: SetEmbeddedData()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a beágyazott OLE adatokra vonatkozó információkat.
type: docs
weight: 248
url: /hu/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metódus


Beágyazott OLE adatokra vonatkozó információk beállítása.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Beágyazott adat [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Megjegyzések


Ez a metódus módosítja az objektum tulajdonságait az új adatok tükrözésére, és a IsObjectLink jelzőt false-ra állítja, jelezve, hogy az OLE objektum be van ágyazva. 



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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Osztály [OleObjectFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)