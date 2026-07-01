---
title: SmartArtShape
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Reprezentuje SmartArt tvar
type: docs
weight: 10640
url: /cs/aspose.slides.smartart/smartartshape/
---
## SmartArtShape třída

Representuje SmartArt tvar

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Vrací kolekci hodnot úprav tvaru. Pouze pro čtení [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem. Čtení/zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar renderován v černobílém režimu zobrazení. Čtení/zápis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Čtení/zápis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Mark as decorative'. Čtení/zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Čtení/zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupce (placeholder) pro tvar. Vrací null, pokud tvar nemá placeholder. Pouze pro čtení [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o který je daný tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/zápis Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Vrací zamky tvaru. Pouze pro čtení [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Vrací objekt stylu tvaru. Pouze pro čtení [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Vrací nebo nastavuje předdefinovaný typ geometrie. Poznámka: při změně hodnoty se všechny hodnoty úpravy resetují na výchozí. Čtení/zápis [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze pro čtení [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Vrací text SmartArt tvaru. Pouze pro čtení [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být přidělena uživatelem nebo programově, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-řazení. Shapes[0] vrací tvar vzadu v z-řazení a Shapes[Shapes.Count - 1] vrací tvar v popředí z-řazení. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový placeholder, pokud žádný není, a nastaví vlastnosti placeholderu na zadaný. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Vytvoří a vrátí pole prvků tvaru. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní placeholder tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen). Vrací null, pokud aktuální tvar není odvozen. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Typ ShapeThumbnailBounds.Shape je použit jako výchozí pro ohraničení miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](../../aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) na Vlastní. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](../../aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) na Vlastní. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [GeometryShape](../../aspose.slides/geometryshape)
* rozhraní [ISmartArtShape](../ismartartshape)
* jmenný prostor [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->