---
title: AddOleObjectFrame
second_title: Aspose.Slides für .NET-API-Referenz
description: Fügt ein neues OLEObjekt am Ende einer Sammlung hinzu.
type: docs
weight: 150
url: /de/net/aspose.slides/shapecollection/addoleobjectframe/
---
## AddOleObjectFrame(float, float, float, float, IOleEmbeddedDataInfo) {#addoleobjectframe}

Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu.

```csharp
public IOleObjectFrame AddOleObjectFrame(float x, float y, float width, float height, 
    IOleEmbeddedDataInfo dataInfo)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen OLE-Rahmens. |
| y | Single | Y-Koordinate eines neuen OLE-Rahmens. |
| width | Single | Breite eines neuen OLE-Rahmens. |
| height | Single | Höhe eines neuen OLE-Rahmens. |
| dataInfo | IOleEmbeddedDataInfo | Eingebettete Dateninfo[`IOleEmbeddedDataInfo`](../../ioleembeddeddatainfo). |

### Rückgabewert

Erstelltes OLE-Objekt.

### Beispiele

Dieses Beispiel zeigt das Hinzufügen eines OLE-Objekts am Ende einer Sammlung:

```csharp
[C#]
byte[] fileData = File.ReadAllBytes("test.zip");
IEmbeddedDataInfo dataInfo = new EmbeddedDataInfo(fileData, "zip");
IOleObjectFrame oleObjectFrame = slidees.Shapes.AddOleObjectFrame(150, 20, 50, 50, dataInfo);
```

### Siehe auch

* interface [IOleObjectFrame](../../ioleobjectframe)
* interface [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo)
* class [ShapeCollection](../../shapecollection)
* namensraum [Aspose.Slides](../../shapecollection)
* Montage [Aspose.Slides](../../../)

---

## AddOleObjectFrame(float, float, float, float, string, string) {#addoleobjectframe_1}

Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu.

```csharp
public IOleObjectFrame AddOleObjectFrame(float x, float y, float width, float height, 
    string className, string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen OLE-Rahmens. |
| y | Single | Y-Koordinate eines neuen OLE-Rahmens. |
| width | Single | Breite eines neuen OLE-Rahmens. |
| height | Single | Höhe eines neuen OLE-Rahmens. |
| className | String | Name einer OLE-Klasse. |
| path | String | Pfad zur verknüpften Datei. |

### Rückgabewert

Erstelltes OLE-Objekt.

### Siehe auch

* interface [IOleObjectFrame](../../ioleobjectframe)
* class [ShapeCollection](../../shapecollection)
* namensraum [Aspose.Slides](../../shapecollection)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->