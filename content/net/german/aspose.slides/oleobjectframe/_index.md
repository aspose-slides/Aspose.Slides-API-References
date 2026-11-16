---
title: OleObjectFrame
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein OLE-Objekt auf einer Folie dar.
type: docs
weight: 9250
url: /de/aspose.slides/oleobjectframe/
---
## OleObjectFrame Klasse

Stellt ein OLE-Objekt auf einer Folie dar.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese/Schreib String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese/Schreib String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IGraphicalObject. Nur-Lesen [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeige-Modus gerendert wird. Lese/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur-Lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte einer Form enthält. Hinweis: Kann für bestimmte Formen, die keine Effekt-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Gibt Informationen über eingebettete OLE-Daten zurück oder legt sie fest. Lese/Schreib [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Gibt den Dateinamen des eingebetteten OLE-Objekts zurück |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Gibt den Pfad des eingebetteten OLE-Objekts zurück |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formen, die keine Füll-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lese/Schreib [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form in Punkten zurück oder legt sie fest. Lese/Schreib Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lese/Schreib Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese/Schreib [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Maus-Überfahren definierten Hyperlink zurück oder legt ihn fest. Lese/Schreib [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest. Lese/Schreib Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesen Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lese/Schreib Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. Nur-Lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linien-Formatierungs-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formen, die keine Linien-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Der Kurzdateiname wird verwendet. Nur-Lesen String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück oder legt ihn fest. Der Langdateiname wird verwendet. Lese/Schreib String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, sonst einen leeren String. Nur-Lesen String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lese/Schreib String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Gibt den Namen eines Objekts zurück oder legt ihn fest. Lese/Schreib String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Gibt die ProgID eines Objekts zurück. Nur-Lesen String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur-Lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls null. Nur-Lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lese/Schreib [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Gegenuhrzeigersinn. Lese/Schreib Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lesen [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Gibt das OleObject-Bildfüll-Eigenschaften-Objekt zurück. Nur-Lesen [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Gibt den Titel für das OleObject-Symbol zurück oder legt ihn fest. Lese/Schreib String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3-D-Effekt-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formen, die keine 3-D-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden. Nur-Lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lese/Schreib Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form in Punkten zurück oder legt sie fest. Lese/Schreib Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form in Punkten zurück oder legt sie fest. Lese/Schreib Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form in Punkten zurück oder legt sie fest. Lese/Schreib Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form im hinteren Teil der Z-Reihenfolge zurück, Shapes[Shapes.Count - 1] die vorderste Form. Nur-Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf den angegebenen. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form erbt). Null wird zurückgegeben, wenn die aktuelle Form nicht geerbt ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Gibt die visuellen Begrenzungen der Form zurück, berechnet aus ihrem gerenderten Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Setzt Informationen über eingebettete OLE-Daten. Diese Methode ändert die Eigenschaften des Objekts, um die neuen Daten widerzuspiegeln, und setzt das IsObjectLink-Flag auf false, was anzeigt, dass das OLE-Objekt eingebettet ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Beispiele

Das folgende Beispiel zeigt, wie auf OLE-Objekt-Frames zugegriffen wird.

```csharp
[C#]
// Lädt die PPTX in ein Präsentationsobjekt
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Greift auf die erste Folie zu
    ISlide sld = pres.Slides[0];
    // Castet das Shape zu OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Liest das OLE-Objekt und schreibt es auf die Festplatte
    if (oleObjectFrame != null)
    {
        // Holt die eingebetteten Dateidaten
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Holt die Erweiterung der eingebetteten Datei
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Erstellt einen Pfad, um die extrahierte Datei zu speichern
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Speichert die extrahierten Daten
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Siehe auch

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->