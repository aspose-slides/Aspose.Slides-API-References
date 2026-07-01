---
title: OleObjectFrame
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett OLE-objekt på en bild.
type: docs
weight: 9210
url: /sv/aspose.slides/oleobjectframe/
---
## OleObjectFrame klass

Representerar ett OLE-objekt på en bild.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Tillåter att hämta bas-IGraphicalObject-gränssnittet. Skrivskyddad [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form ska renderas i svart-vit visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningsplatser på formen. Skrivskyddad Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form. Observera: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Hämtar eller anger information om OLE-inbäddade data. Läs/skriv [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Returnerar filnamnet för det inbäddade OLE-objektet |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Returnerar sökvägen för det inbäddade OLE-objektet |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller ifyllningsformat-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har ifyllnings-egenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Skrivskyddad [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Avgör om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänks-hanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för musövergång. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Avgör om formen är grupperad. Skrivskyddad Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Avgör om ett objekt är synligt som ikon. Läs/skriv Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Avgör om ett objekt är länkat till en extern fil. Skrivskyddad Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Avgör om formen är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformat-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har linje-egenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Returnerar den fullständiga sökvägen till en länkad fil. Kort filnamn kommer att användas. Skrivskyddad String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Returnerar den fullständiga sökvägen till en länkad fil. Långt filnamn kommer att användas. Läs/skriv String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. Skrivskyddad String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Får inte vara null. Använd tom sträng om så behövs. Läs/skriv String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Returnerar eller anger namnet på ett objekt. Läs/skriv String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Returnerar ProgID för ett objekt. Skrivskyddad String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-specifik unik identifierare som förblir konstant under formens livslängd och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken plats som helst i dokumentet. Skrivskyddad UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar överordnat GroupShape-objekt om formen är grupperad. Annars returneras null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den specificerade formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Skrivskyddad [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 egenskaper) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Returnerar OleObject-bildens ifyllnings-egenskapsobjekt. Skrivskyddad [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Returnerar eller anger titeln för OleObject-ikonen. Läs/skriv String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en beständig unik nyckel. Skrivskyddad UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Avgör om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. Läs/skriv Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyr. ShapeThumbnailBounds.Shape-typ för miniatyrens gränser används som standard. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyr. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Sätter information om OLE-inbäddade data. Denna metod ändrar objektets egenskaper för att återspegla de nya data och sätter IsObjectLink-flaggan till false, vilket indikerar att OLE-objektet är inbäddat. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar formens innehåll som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar formens innehåll som en SVG-fil. |

### Exempel

Följande exempel visar hur man får åtkomst till OLE-objektramar.

```csharp
[C#]
// Laddar PPTX till ett presentationsobjekt
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Åtkomst till den första bilden
    ISlide sld = pres.Slides[0];
    // Konverterar formen till OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Läser OLE-objektet och skriver det till disk
    if (oleObjectFrame != null)
    {
        // Hämtar inbäddad fildata
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Hämtar inbäddad filändelse
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Skapar en sökväg för att spara den extraherade filen
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Sparar extraherad data
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Se även

* klass [GraphicalObject](../graphicalobject)
* gränssnitt [IOleObjectFrame](../ioleobjectframe)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->