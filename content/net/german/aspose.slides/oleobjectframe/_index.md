---
title: OleObjectFrame
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt ein OLE-Objekt auf einer Folie dar.
type: docs
weight: 9230
url: /de/aspose.slides/oleobjectframe/
---
## OleObjectFrame Klasse

Represents an OLE object on a slide.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Liefert oder setzt den alternativen Text, der mit einer Form verknüpft ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Liefert oder setzt den Titel des alternativen Texts, der mit einer Form verknüpft ist. Lesen/Schreiben String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IGraphicalObject. Nur lesen [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Liefert die Anzahl der Verbindungsstellen der Form. Nur lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Liefert die benutzerdefinierten Daten der Form. Nur lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Liefert das EffectFormat-Objekt, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen. Nur lesen [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Liest oder setzt Informationen über OLE-eingebettete Daten. Lesen/Schreiben [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Liefert den Dateinamen des eingebetteten OLE-Objekts |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Liefert den Pfad des eingebetteten OLE-Objekts |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Liefert das FillFormat-Objekt, das Füllformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen. Nur lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Liefert oder setzt die Eigenschaften des Formrahmens. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Liefert die Sperren der Form. Nur lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Liest oder setzt die Höhe der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Liefert oder setzt den für Mausklick definierten Hyperlink. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Liefert den Hyperlink-Manager. Nur lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Liefert oder setzt den für Maus-over definierten Hyperlink. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Liest oder setzt die Option „Als dekorativ markieren“. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesen Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lesen/Schreiben Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. Nur lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Liefert das LineFormat-Objekt, das Linienformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Linien-Eigenschaften besitzen. Nur lesen [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Liefert den vollständigen Pfad zu einer verknüpften Datei. Kurzdateiname wird verwendet. Nur lesen String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Liefert den vollständigen Pfad zu einer verknüpften Datei. Langdateiname wird verwendet. Lesen/Schreiben String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Liefert den relativen Pfad zu einer verknüpften Datei, falls vorhanden, sonst einen leeren String. Nur lesen String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Liefert oder setzt den Namen einer Form. Darf nicht null sein. Bei Bedarf leeren String verwenden. Lesen/Schreiben String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Liefert oder setzt den Namen eines Objekts. Lesen/Schreiben String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Liefert die ProgID eines Objekts. Nur lesen String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Liefert einen folienbezogenen eindeutigen Bezeichner, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code erlaubt, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Liefert das übergeordnete GroupShape-Objekt, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Liefert den Platzhalter für eine Form. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Liefert die übergeordnete Präsentation einer Folie. Nur lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Liefert oder setzt die rohen Eigenschaften des Formrahmens. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Liefert oder setzt die Anzahl der Grad, um die die angegebene Form um die Z-Achse gedreht wird. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Liefert die Sperren der Form. Nur lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Liefert die übergeordnete Folie einer Form. Nur lesen [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Liefert das Objekt für Bildfüll-Eigenschaften des OleObject. Nur lesen [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Liefert oder setzt den Titel für das OleObject-Symbol. Lesen/Schreiben String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Liefert das ThreeDFormat-Objekt, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen. Nur lesen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Liefert einen internen, präsentationsbezogenen Bezeichner, der für Add-ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel verwendet werden. Nur lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lesen/Schreiben Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Liest oder setzt die Breite der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Liefert die Position einer Form in der Z-Reihenfolge. Shapes[0] liefert die Form ganz hinten, und Shapes[Shapes.Count - 1] liefert die Form ganz vorne. Nur lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Liefert eine einfache Platzhalter-Form (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt). Null wird zurückgegeben, wenn die aktuelle Form nicht vererbt ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Liefert das Form-Thumbnail. Standardmäßig wird der Typ ShapeThumbnailBounds.Shape für die Thumbnail-Grenzen verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Liefert das Form-Thumbnail. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Setzt Informationen zu OLE-eingebetteten Daten. Diese Methode ändert die Eigenschaften des Objekts, um die neuen Daten widerzuspiegeln, und setzt das IsObjectLink-Flag auf false, was anzeigt, dass das OLE-Objekt eingebettet ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Beispiele

Das folgende Beispiel zeigt, wie man OLE-Objekt-Frames verwendet.

```csharp
[C#]
// Lädt die PPTX in ein Präsentationsobjekt
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Greift auf die erste Folie zu
    ISlide sld = pres.Slides[0];
    // Castet die Form zu OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Liest das OLE-Objekt und schreibt es auf die Festplatte
    if (oleObjectFrame != null)
    {
        // Holt die eingebetteten Dateidaten
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Holt die Erweiterung der eingebetteten Datei
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Erstellt einen Pfad zum Speichern der extrahierten Datei
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Speichert extrahierte Daten
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Siehe auch

* Klasse [GraphicalObject](../graphicalobject)
* Interface [IOleObjectFrame](../ioleobjectframe)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->