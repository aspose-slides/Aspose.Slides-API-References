---
title: Ink
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een inktobject voor op een dia.
type: docs
weight: 7550
url: /nl/aspose.slides.ink/ink/
---
## Ink klasse

Stelt een inktobject voor op een dia.

```csharp
public class Ink : GraphicalObject, IInk
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourneert het FillFormat-object dat opvul-opmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen opvul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het vormkader in. Lezen/Schrijven [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt op of stelt de hoogte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlink-manager. Alleen-lezen [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/Schrijven [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt op of stelt de optie 'Mark as decorative' in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijstopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een unieke identifier binnen de dia die gedurende de levensduur van de vorm constant blijft en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elke plaats in het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de tijdelijke aanduiding voor een vorm. Retourneert null als de vorm geen tijdelijke aanduiding heeft. Alleen-lezen [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe eigenschappen van het vormkader in. Lezen/Schrijven [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt een rotatie met de klok mee aan; een negatieve waarde duidt een rotatie tegen de klok in aan. Lezen/Schrijven Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 eigenschappen) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Haalt alle sporen op die zich in het IInk-element [`IInkTrace`](../iinktrace) bevinden. Alleen-lezen. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, binnen de presentatie gescoped identifier die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hergebruikt, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt op of stelt de breedte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde. Alleen-lezen Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Haalt de collectie van aangepaste afbeeldingen op die worden gebruikt om visuele effecten voor inkt-penseelsteken te simuleren. Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke [`InkEffectType`](../inkeffecttype) waarden, zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te voorzien, kunt u bepalen hoe elk inkt-effect verschijnt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen bestaat en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven één. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-tijdelijke-aanduidings-vorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd). Null wordt geretourneerd als de huidige vorm niet is geërfd. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor de miniatuur-grenzen. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op die zijn berekend uit de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IInk](../iink)
* namespace [Aspose.Slides.Ink](../../aspose.slides.ink)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->