---
title: Connector
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een connector voor.
type: docs
weight: 2690
url: /nl/aspose.slides/connector/
---
## Connector klasse

Stelt een connector voor.

```csharp
public class Connector : GeometryShape, IConnector
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retourneert een verzameling van aanpassingswaarden van de vorm. Alleen-lezen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal verbindingsplaatsen op de vorm. Alleen-lezen Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Retourneert de vergrendelingen van de connector. Alleen-lezen [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Retourneert of stelt de vorm in waaraan het uiteinde van de connector wordt gekoppeld. Lezen/schrijven [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Retourneert of stelt de index van de verbindingsplaats voor de eindvorm in. Lezen/schrijven UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourneert het FillFormat-object dat opvul-opmaak eigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde vormen die geen opvul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het shape-frame in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt of stelt de hoogte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlink-beheerder. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt of stelt de optie 'Markeer als decoratief' in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijn-opmaak eigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een dia-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de tijdelijke aanduiding voor een vorm. Retourneert null als de vorm geen tijdelijke aanduiding heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe shape-frame-eigenschappen in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm wordt geroteerd rond de z-as. Een positieve waarde geeft een klokrichting rotatie aan; een negatieve waarde een tegen-klokrichting rotatie. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IConnectorLock`](../iconnectorlock). (2 eigenschappen) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retourneert het stijloobject van de vorm. Alleen-lezen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Retourneert of stelt het AutoShape-type in. Lezen/schrijven [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. Lezen/schrijven [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Retourneert of stelt de index van de verbindingsplaats voor de startvorm in. Lezen/schrijven UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, presentatie-specifieke identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden aangepast, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt of stelt de breedte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen bestaat en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Maakt een array van elementen van de vorm aan en retourneert deze. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-tijdelijke-aanduidingsvorm (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd). Retourneert null als de huidige vorm niet is geërfd. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retourneert een kopie van het pad van de geometrievorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. Standaard wordt het type ShapeThumbnailBounds.Shape gebruikt voor de miniatuuropslag. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [Reroute](../../aspose.slides/connector/reroute)() | Herleidt de connector zodat deze het kortste mogelijke pad tussen de vormen die hij verbindt neemt. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Werkt de geometrie van de vorm bij vanuit [`IGeometryPath`](../igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Verandert het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Werkt de geometrie van de vorm bij vanuit een array van [`IGeometryPath`](../igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Verandert het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van Shape op als SVG-bestand. |

### Zie ook

* klasse [GeometryShape](../geometryshape)
* interface [IConnector](../iconnector)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->