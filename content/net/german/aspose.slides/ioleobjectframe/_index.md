---
title: IOleObjectFrame
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein OLE-Objekt auf einer Folie dar.
type: docs
weight: 6340
url: /de/aspose.slides/ioleobjectframe/
---

## IOleObjectFrame-Schnittstelle

Stellt ein OLE-Objekt auf einer Folie dar.

```csharp
public interface IOleObjectFrame : IGraphicalObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIGraphicalObject](../../aspose.slides/ioleobjectframe/asigraphicalobject) { get; } | Ermöglicht den Zugriff auf die Basis-IGraphicalObject-Schnittstelle. Nur lesbar [`IGraphicalObject`](../igraphicalobject). |
| [EmbeddedData](../../aspose.slides/ioleobjectframe/embeddeddata) { get; } | Erhält Informationen über OLE eingebettete Daten. Nur lesbar [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/ioleobjectframe/embeddedfilelabel) { get; } | Gibt den Dateinamen des eingebetteten OLE-Objekts zurück |
| [EmbeddedFileName](../../aspose.slides/ioleobjectframe/embeddedfilename) { get; } | Gibt den Pfad des eingebetteten OLE-Objekts zurück |
| [IsObjectIcon](../../aspose.slides/ioleobjectframe/isobjecticon) { get; set; } | Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lese-/Schreib-Boolean. |
| [IsObjectLink](../../aspose.slides/ioleobjectframe/isobjectlink) { get; } | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. Nur lesbarer Boolean. |
| [LinkFileName](../../aspose.slides/ioleobjectframe/linkfilename) { get; } | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Es wird der kurze Dateiname verwendet. Nur lesbare Zeichenfolge. |
| [LinkPathLong](../../aspose.slides/ioleobjectframe/linkpathlong) { get; set; } | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Es wird der lange Dateiname verwendet. Lese-/Schreib-Zeichenfolge. |
| [LinkPathRelative](../../aspose.slides/ioleobjectframe/linkpathrelative) { get; } | Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, andernfalls wird eine leere Zeichenfolge zurückgegeben. Nur lesbare Zeichenfolge. |
| [ObjectName](../../aspose.slides/ioleobjectframe/objectname) { get; set; } | Gibt den Namen eines Objekts zurück oder legt ihn fest. Lese-/Schreib-Zeichenfolge. |
| [ObjectProgId](../../aspose.slides/ioleobjectframe/objectprogid) { get; set; } | Gibt die ProgID eines Objekts zurück. Nur lesbare Zeichenfolge. |
| [SubstitutePictureFormat](../../aspose.slides/ioleobjectframe/substitutepictureformat) { get; } | Gibt das Objekt der Füll Eigenschaften für OleObject-Bilder zurück. Nur lesbar [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/ioleobjectframe/substitutepicturetitle) { get; set; } | Gibt den Titel für das OleObject-Symbol zurück oder legt ihn fest. Lese-/Schreib-Zeichenfolge. |
| [UpdateAutomatic](../../aspose.slides/ioleobjectframe/updateautomatic) { get; set; } | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lese-/Schreib-Boolean. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetEmbeddedData](../../aspose.slides/ioleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Setzt Informationen über OLE eingebettete Daten. |

### Siehe auch

* Schnittstelle [IGraphicalObject](../igraphicalobject)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->