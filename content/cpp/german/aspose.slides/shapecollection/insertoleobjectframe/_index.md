---
title: InsertOleObjectFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Position in die Shape-Collection ein.
type: docs
weight: 196
url: /de/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Creates a new OLE object frame and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das OLE-Objektrahmen eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen OLE-Rahmens in Punkten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Return Value

Das neu erstellte [IOleObjectFrame](../../ioleobjectframe/).

## Remarks



Dieses Beispiel zeigt das Einfügen eines OLE-Objekts am zweiten Index: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method


Creates a new OLE object frame and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das OLE-Objektrahmen eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen OLE-Rahmens in Punkten. |
| className | [System::String](../../../system/string/) | Der Klassenname des OLE-Objekts. |
| path | [System::String](../../../system/string/) | Der Pfad zur verknüpften Datei. |

### Return Value

Der neu erstellte OLE-Objektrahmen.

## Remarks



Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOleObjectFrame](../../ioleobjectframe/)
* Klasse [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasse [ShapeCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)