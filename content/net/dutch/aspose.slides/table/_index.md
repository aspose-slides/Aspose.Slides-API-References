---
title: Table
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een tabel op een dia voor.
type: docs
weight: 10880
url: /nl/aspose.slides/table/
---
## Table klasse

Stelt een tabel op een dia voor.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus.. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Geeft de verzameling kolommen terug. Alleen-lezen [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten op de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm worden toegepast. Opmerking: kan null teruggeven voor bepaalde vormen die geen effect-eigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Geeft een TableFormat.FillFormat-object terug dat de opvulopmaak voor de tabel bevat. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen/Schrijven Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. Lezen/Schrijven Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Geeft de eigenschappen van het vormkader terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Geeft de hoogte van de vorm terug of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Bepaalt of de even rijen met een andere opmaak moeten worden getekend. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muisklik terug of stelt deze in. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlink-beheerder terug. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muis-over terug of stelt deze in. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Geeft de optie 'Mark as decorative' terug of stelt deze in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Geeft de cel terug op de opgegeven kolom- en rij-indexen. Alleen-lezen [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Bepaalt of de laatste kolom van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Bepaalt of de laatste rij van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Geeft de naam van een vorm terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een unieke identifier scoped per dia terug die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt null teruggegeven. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de plaatsaanduiding voor een vorm terug. Retourneert null als de vorm geen plaatsaanduiding heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een dia terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Geeft de ruwe eigenschappen van het vormkader terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Bepaalt of de tabel een rechts-naar-links leervoorraad heeft. Lezen/Schrijven Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Geeft het aantal graden terug of stelt deze in waarmee de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde duidt een klokwijs rotatie aan; een negatieve waarde een tegen-klokwijs rotatie. Lezen/Schrijven Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Geeft de verzameling rijen terug. Alleen-lezen [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 eigenschappen) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende dia van een vorm terug. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Geeft de ingebouwde tabelstijl terug of stelt deze in. Lezen/Schrijven [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Geeft het TableFormat-object terug dat opmaak-eigenschappen voor deze tabel bevat. Alleen-lezen [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3D-effect-eigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, per presentatie gescoped identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden beschouwd als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. Lezen/Schrijven Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Geeft de breedte van de vorm terug of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Geeft de x-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Geeft de y-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] geeft de vorm aan de achterkant van de z-volgorde terug, en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde terug. Alleen-lezen Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe plaatsaanduiding toe als er geen is en stelt de eigenschappen van de plaatsaanduiding in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basisplaatsaanduidingsvorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet is geërfd. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. Het type ShapeThumbnailBounds.Shape wordt standaard gebruikt voor de miniatuurboundaries. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Geeft de visuele grenzen van de vorm terug, berekend uit de gerenderde inhoud. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Voegt naburige cellen samen. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen plaatsaanduiding is. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Stelt de gedefinieerde alinea-opmaak-eigenschappen in voor alle alinea's van tabelcellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Stelt de gedefinieerde gedeelte-opmaak-eigenschappen in voor alle gedeelten van tabelcellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Stelt de gedefinieerde tekstframe-opmaak-eigenschappen in voor alle tekstframes van tabelcellen. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* klasse [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->