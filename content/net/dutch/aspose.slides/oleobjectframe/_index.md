---
title: OleObjectFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een OLE-object op een dia voor.
type: docs
weight: 9250
url: /nl/aspose.slides/oleobjectframe/
---
## OleObjectFrame klasse

Stelt een OLE-object op een dia voor.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Staat toe de basis-IGraphicalObject interface op te halen. Alleen-lezen [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Haalt op of stelt informatie over OLE-embedded data in. Lezen/schrijven [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Retourneert de bestandsnaam van het ingebedde OLE-object |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Retourneert het pad van het ingebedde OLE-object |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourneert het FillFormat-object dat opvul-opmaak eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen opvul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de vormframe-eigenschappen in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt op of stelt de hoogte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlink-manager. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt op of stelt de optie 'Mark as decorative' in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Bepaalt of een object zichtbaar is als pictogram. Lezen/schrijven Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Bepaalt of een object gekoppeld is aan een extern bestand. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijn-opmaak eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Retourneert het volledige pad naar een gekoppeld bestand. Korte bestandsnaam wordt gebruikt. Alleen-lezen String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam wordt gebruikt. Lezen/schrijven String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders een lege string. Alleen-lezen String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege string indien nodig. Lezen/schrijven String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Retourneert of stelt de naam van een object in. Lezen/schrijven String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Retourneert de ProgID van een object. Alleen-lezen String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een dia-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code betrouwbaar laat verwijzen naar de vorm vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de tijdelijke aanduiding voor een vorm. Retourneert null als de vorm geen tijdelijke aanduiding heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe vormframe-eigenschappen in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt geroteerd. Een positieve waarde geeft klokwijzerrotatie aan; een negatieve waarde geeft tegen-klokwijzerrotatie aan. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 eigenschappen) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Retourneert OleObject-afbeeldingsvulling-eigenschappen object. Alleen-lezen [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Retourneert of stelt de titel voor het OleObject-pictogram in. Lezen/schrijven String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, presentatie-specifieke identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herschikt, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Bepaalt of het gekoppelde ingebedde object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lezen/schrijven Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt op of stelt de breedte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] geeft de vorm aan het einde van de z-volgorde, en Shapes[Shapes.Count - 1] geeft de vorm aan het begin van de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. Standaard wordt ShapeThumbnailBounds.Shape miniatuurbounds-type gebruikt. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Stelt informatie over OLE-embedded data in. Deze methode wijzigt de eigenschappen van het object om de nieuwe data weer te geven en zet de IsObjectLink-vlag op false, wat aangeeft dat het OLE-object is ingebed. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van Shape op als SVG-bestand. |

### Voorbeelden

```csharp
[C#]
// Laadt de PPTX naar een presentatie-object
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Toegang tot de eerste dia
    ISlide sld = pres.Slides[0];
    // Castt de vorm naar OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Leest het OLE Object en schrijft het naar schijf
    if (oleObjectFrame != null)
    {
        // Haalt embedded bestandsgegevens op
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Haalt embedded bestandsextensie op
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Maakt een pad aan om het geëxtraheerde bestand op te slaan
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Slaat geëxtraheerde gegevens op
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
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->