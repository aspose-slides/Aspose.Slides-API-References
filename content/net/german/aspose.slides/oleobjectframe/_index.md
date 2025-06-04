---
title: OleObjectFrame
second_title: Aspose.Slides für .NET API Referenz
description: Stellt ein OLE-Objekt auf einer Folie dar.
type: docs
weight: 8960
url: /de/aspose.slides/oleobjectframe/
---

## OleObjectFrame-Klasse

Stellt ein OLE-Objekt auf einer Folie dar.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des zugehörigen alternativen Texts einer Form zurück oder legt ihn fest. Lese-/Schreibzugriff String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Ermöglicht den Zugriff auf die Basis-I-GraphicalObject-Schnittstelle. Nur Lesezugriff [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Gibt an, wie eine Form im Schwarz-Weiß-Displaymodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Effekt-Eigenschaften haben. Nur Lesezugriff [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Ruft Informationen über OLE eingebettete Daten ab oder legt sie fest. Lese-/Schreibzugriff [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Gibt den Dateinamen des eingebetteten OLE-Objekts zurück |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Gibt den Pfad des eingebetteten OLE-Objekts zurück |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Füll-Eigenschaften haben. Nur Lesezugriff [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den definierten Hyperlink für Mausklick zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den definierten Hyperlink für Mouseover zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ruft die Option 'Als dekorativ markieren' ab oder legt sie fest. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lese-/Schreibzugriff Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. Nur Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur Lesezugriff Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Linien-Eigenschaften haben. Nur Lesezugriff [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Gibt den vollständigen Pfad zu einer verlinkten Datei zurück. Der kurze Dateiname wird verwendet. Nur Lesezugriff String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Gibt den vollständigen Pfad zu einer verlinkten Datei zurück. Der lange Dateiname wird verwendet. Lese-/Schreibzugriff String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Gibt den relativen Pfad zu einer verlinkten Datei zurück, wenn vorhanden; andernfalls wird ein leerer String zurückgegeben. Nur Lesezugriff String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Muss nicht null sein. Verwenden Sie den leeren String-Wert, wenn erforderlich. Lese-/Schreibzugriff String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Gibt den Namen eines Objekts zurück oder legt ihn fest. Lese-/Schreibzugriff String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Gibt die ProgID eines Objekts zurück. Nur Lesezugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft den eindeutigen Formen-Identifikator im Folienkontext ab. Nur Lesezugriff UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für den Abruf des einzigartigen Formen-Identifikators im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur Lesezugriff [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Rohdaten der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse gedreht ist. Ein positiver Wert deutet auf eine Drehung im Uhrzeigersinn hin; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Gibt das OleObject-Bildfüllformatierungsobjekt zurück. Nur Lesezugriff [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Gibt den Titel für das OleObject-Symbol zurück oder legt ihn fest. Lese-/Schreibzugriff String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur Lesezugriff [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft den eindeutigen Formen-Identifikator im Präsentationskontext ab. Nur Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für den Abruf des einzigartigen Formen-Identifikators im Folienkontext. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Bestimmt, ob das verbundene eingebettete Objekt beim Öffnen oder Drucken der Präsentation automatisch aktualisiert wird. Lese-/Schreibzugriff Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Reihenfolge zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist und legt die Platzhaltereigenschaften auf eine bestimmte fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von der Vorlage und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Thumbnail der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Thumbnail der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Legt Informationen über OLE eingebettete Daten fest. Diese Methode ändert die Eigenschaften des Objekts, um die neuen Daten widerzuspiegeln, und setzt das IsObjectLink-Flag auf false, was bedeutet, dass das OLE-Objekt eingebettet ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Beispiele

Das folgende Beispiel zeigt, wie OLE-Objektrahmen zugegriffen werden.

```csharp
[C#]
// Lädt die PPTX in ein Präsentationsobjekt
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Greift auf die erste Folie zu
    ISlide sld = pres.Slides[0];
    // Wandelt die Form in OleObjectFrame um
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Liest das OLE-Objekt und schreibt es auf die Festplatte
    if (oleObjectFrame != null)
    {
        // Ruft die embedded file data ab
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Ruft die embedded file extension ab
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

* Klasse [GraphicalObject](../graphicalobject)
* Schnittstelle [IOleObjectFrame](../ioleobjectframe)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->