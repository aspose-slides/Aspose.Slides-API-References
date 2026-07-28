---
title: InsertOleObjectFrame()
second_title: Aspose.Slides a C++ API referencia
description: Új OLE objektumkeretet hoz létre, és a megadott indexen beszúrja a alakzatgyűjteménybe.
type: docs
weight: 196
url: /hu/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Új OLE objektumkeretet hoz létre, és a megadott indexen beszúrja a alakzatgyűjteménybe.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nullától indított index, amelyen az OLE objektumkeretet be kell szúrni. |
| x | **float** | Az új OLE keret x koordinátája pontban. |
| y | **float** | Az új OLE keret y koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Return Value

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).

## Remarks

Ez a példa bemutatja egy OLE objektum beszúrását a második indexre:
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method

Új OLE objektumkeretet hoz létre, és a megadott indexen beszúrja a alakzatgyűjteménybe.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nullától indított index, amelyen az OLE objektumkeretet be kell szúrni. |
| x | **float** | Az új OLE keret x koordinátája pontban. |
| y | **float** | Az új OLE keret y koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| className | [System::String](../../../system/string/) | Az OLE objektum osztályneve. |
| path | [System::String](../../../system/string/) | A hivatkozott fájl elérési útja. |

### Return Value

Az újonnan létrehozott OLE objektumkeret.

## Remarks

Ez az útvonal változatlanul kerül tárolásra a bemutatóban. Ha relatív útvonal van megadva, a fájl elérhetetlen lesz, ha a bemutatót egy másik könyvtárból nyitja meg.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IOleObjectFrame](../../ioleobjectframe/)
* Osztály [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Osztály [ShapeCollection](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)