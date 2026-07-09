---
title: OleObjectFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Vertegenwoordigt een OLE-object op een dia.
type: docs
weight: 9230
url: /nl/aspose.slides/oleobjectframe/
---
## OleObjectFrame klasse

Represents an OLE object on a slide.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Haalt de alternatieve tekst op of stelt deze in voor een vorm. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Haalt de titel van de alternatieve tekst op of stelt deze in voor een vorm. Lezen/schrijven String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Staat toe de basis IGraphicalObject interface op te halen. Alleen-lezen [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten van de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm worden toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Haalt informatie over OLE-embedded data op of stelt deze in. Lezen/schrijven [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Geeft de bestandsnaam van het embedded OLE-object terug |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Geeft het pad van het embedded OLE-object terug |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Geeft het FillFormat-object terug dat vulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen vul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Haalt de eigenschappen van het vormframe op of stelt deze in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt de hoogte van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Haalt de hyperlink op die is gedefinieerd voor muisklik, of stelt deze in. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlinkbeheerder terug. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Haalt de hyperlink op die is gedefinieerd voor muisover, of stelt deze in. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt de optie 'Mark as decorative' op of stelt deze in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Bepaalt of een object zichtbaar is als pictogram. Lezen/schrijven Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Bepaalt of een object gelinkt is aan een extern bestand. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Geeft het volledige pad naar een gekoppeld bestand terug. Korte bestandsnaam wordt gebruikt. Alleen-lezen String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Geeft het volledige pad naar een gekoppeld bestand terug. Lange bestandsnaam wordt gebruikt. Lezen/schrijven String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Geeft het relatieve pad naar een gekoppeld bestand terug indien aanwezig, anders een lege tekenreeks. Alleen-lezen String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Haalt de naam van een vorm op of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Haalt de naam van een object op of stelt deze in. Lezen/schrijven String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Geeft de ProgID van een object terug. Alleen-lezen String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een slide-specifieke unieke identifier terug die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de placeholder voor een vorm terug. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een slide terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Haalt de ruwe vormframe-eigenschappen op of stelt deze in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Haalt het aantal graden op dat de opgegeven vorm rond de z-as wordt gedraaid, of stelt dit in. Een positieve waarde geeft een klokwijzer rotatie aan; een negatieve waarde een tegen-de-klokwijzer rotatie. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 eigenschappen) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende slide van een vorm terug. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Geeft het OleObject-afbeelding-vulling-eigenschappenobject terug. Alleen-lezen [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Haalt de titel van het OleObject-pictogram op of stelt deze in. Lezen/schrijven String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, presentatie-specifieke identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Bepaalt of het gekoppelde embedded object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lezen/schrijven Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt de breedte van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een vorm in de z-orde terug. Shapes[0] geeft de vorm achterin de z-orde, en Shapes[Shapes.Count - 1] geeft de vorm vooraan in de z-orde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Geeft een basis placeholder-vorm terug (vorm van de lay-out en/of master slide waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet is geërfd. |
| [GetImage](../../aspose.slides/shape/getimage)() | Geeft de miniatuur van de vorm terug. Standaard wordt het type ShapeThumbnailBounds.Shape gebruikt. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Geeft de miniatuur van de vorm terug. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Stelt informatie over OLE-embedded data in. Deze methode wijzigt de eigenschappen van het object zodat ze de nieuwe gegevens weerspiegelen en zet de IsObjectLink-vlag op false, wat aangeeft dat het OLE-object embedded is. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van Shape op als SVG-bestand. |

### Voorbeelden

Het volgende voorbeeld toont hoe OLE Object-frames te benaderen.

```csharp
[C#]
// Laadt de PPTX naar een presentatieobject
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Toegang tot de eerste dia
    ISlide sld = pres.Slides[0];
    // Cast de vorm naar OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Leest het OLE-object en schrijft het naar schijf
    if (oleObjectFrame != null)
    {
        // Haalt de embedded bestandsgegevens op
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Haalt de extensie van het embedded bestand op
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Maakt een pad aan om het geëxtraheerde bestand op te slaan
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Slaat de geëxtraheerde gegevens op
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Zie ook

* klasse [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->