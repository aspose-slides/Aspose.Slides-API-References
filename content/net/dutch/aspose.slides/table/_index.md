---
title: Table
second_title: Aspose.Sildes voor .NET API-referentie
description: Representeert een tabel op een dia.
type: docs
weight: 10860
url: /nl/aspose.slides/table/
---
## Table klasse

Representeert een tabel op een dia.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Retourneert de collectie van kolommen. Alleen-lezen [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Retourneert een TableFormat.FillFormat-object dat de opvulopmaak voor de Table bevat. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Bepaalt of de eerste kolom van een tabel getekend moet worden met een speciale opmaak. Lezen/Schrijven Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Bepaalt of de eerste rij van een tabel getekend moet worden met een speciale opmaak. Lezen/Schrijven Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het vormframe in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt op of stelt de hoogte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Bepaalt of de even rijen getekend moeten worden met een andere opmaak. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlinkbeheerder. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt op of stelt de optie 'Mark as decorative' in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Retourneert de cel op de opgegeven kolom- en rij-indexen. Alleen-lezen [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Bepaalt of de laatste kolom van een tabel getekend moet worden met een speciale opmaak. Lezen/Schrijven Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Bepaalt of de laatste rij van een tabel getekend moet worden met een speciale opmaak. Lezen/Schrijven Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks als dat nodig is. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een uniek identificatie-nummer scoped per dia dat constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders retourneert het null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe vormframe-eigenschappen in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Bepaalt of de tabel een van-rechts-naar-links leesvolgorde heeft. Lezen/Schrijven Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in dat de opgegeven vorm draait rond de z-as. Een positieve waarde geeft een rechtsomgaande rotatie aan; een negatieve waarde geeft een tegen-klokrotatie aan. Lezen/Schrijven Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Retourneert de collectie van rijen. Alleen-lezen [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 eigenschappen) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Haalt op of stelt de ingebouwde tabelstijl in. Lezen/Schrijven [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Retourneert het TableFormat-object dat opmaak-eigenschappen voor deze tabel bevat. Alleen-lezen [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, per presentatie gescopeerde identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, mag deze niet worden beschouwd als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Bepaalt of de even kolommen getekend moeten worden met een andere opmaak. Lezen/Schrijven Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt op of stelt de breedte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm aan de achterkant van de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm aan de voorkant van de z-volgorde. Alleen-lezen Int32. |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-placeholder-vorm (vorm uit de lay-out en/of masterslide waarvan de huidige vorm is geërfd). Null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor miniatuurboundaries. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Voegt aangrenzende cellen samen. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Stelt de gedefinieerde alineavormateigenschappen in voor alle alinea's van tabelcellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Stelt de gedefinieerde deel-formateigenschappen in voor alle delen van tabelcellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Stelt de gedefinieerde tekstframe-formateigenschappen in voor alle tekstframes van tabelcellen. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* klasse [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->