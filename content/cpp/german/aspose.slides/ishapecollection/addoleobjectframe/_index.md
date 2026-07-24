---
title: AddOleObjectFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.
type: docs
weight: 66
url: /de/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) Methode

Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen OLE-Rahmens, in Punkten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Return Value

Das neu erstellte [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) Methode

Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen OLE-Rahmens, in Punkten. |
| className | [System::String](../../../system/string/) | Der Klassenname des OLE-Objekts. |
| path | [System::String](../../../system/string/) | Der Pfad zur verknüpften Datei. |

### Return Value

Das neu erstellte [IOleObjectFrame](../../ioleobjectframe/).

## Remarks

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wenn ein relativer Pfad angegeben wird, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOleObjectFrame](../../ioleobjectframe/)
* Klasse [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasse [IShapeCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)