---
title: Ink
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje objekt inkoustu na snímku.
type: docs
weight: 7570
url: /cs/aspose.slides.ink/ink/
---
## Ink třída

Reprezentuje objekt inkoustu na snímku.

```csharp
public class Ink : GraphicalObject, IInk
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s objektem. Číst/Zapisovat String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s objektem. Číst/Zapisovat String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude objekt vykreslen v černobílém režimu zobrazení. Číst/Zapisovat [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet míst připojení na objektu. Pouze ke čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data objektu. Pouze ke čtení [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na objekt. Poznámka: může vrátit null pro určité typy objektů, které nemají vlastnosti efektu. Pouze ke čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro objekt. Poznámka: může vrátit null pro určité typy objektů, které nemají vlastnosti výplně. Pouze ke čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámečku objektu. Číst/Zapisovat [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky objektu. Pouze ke čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získává nebo nastavuje výšku objektu, měřenou v bodech. Číst/Zapisovat Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je objekt skrytý. Číst/Zapisovat Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Číst/Zapisovat [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze ke čtení [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Číst/Zapisovat [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získává nebo nastavuje možnost 'Označit jako dekorativní'. Číst/Zapisovat Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je objekt seskupen. Pouze ke čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je objekt TextHolder_PPT. Pouze ke čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro objekt. Poznámka: může vrátit null pro určité typy objektů, které nemají vlastnosti čáry. Pouze ke čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název objektu. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Číst/Zapisovat String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence objektu a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na objekt odkudkoli v dokumentu. Pouze ke čtení UInt32. Viz také [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací rodičovský objekt GroupShape, pokud je objekt seskupen. Jinak vrací null. Pouze ke čtení [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný objekt pro objekt. Vrací null, pokud objekt nemá zástupný objekt. Pouze ke čtení [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací rodičovskou prezentaci snímku. Pouze ke čtení [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámečku objektu. Číst/Zapisovat [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je objekt otáčen kolem osy z. Kladná hodnota označuje otáčení ve směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Číst/Zapisovat Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky objektu. Pouze ke čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 vlastnosti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací rodičovský snímek objektu. Pouze ke čtení [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro objekt. Poznámka: může vrátit null pro určité typy objektů, které nemají 3D vlastnosti. Pouze ke čtení [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Získává všechny stopy obsažené v elementu IInk [`IInkTrace`](../iinktrace). Pouze ke čtení. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro doplňky nebo jiný kód. Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč. Pouze ke čtení UInt32. Viz také [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získává nebo nastavuje šířku objektu, měřenou v bodech. Číst/Zapisovat Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získává nebo nastavuje souřadnici x levého horního rohu objektu, měřenou v bodech. Číst/Zapisovat Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získává nebo nastavuje souřadnici y levého horního rohu objektu, měřenou v bodech. Číst/Zapisovat Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici objektu v z-řádku. Shapes[0] vrací objekt na zadní straně z-řádku a Shapes[Shapes.Count - 1] vrací objekt na přední straně z-řádku. Pouze ke čtení Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Získává kolekci vlastních obrázků použité k simulaci vizuálních efektů pro inkoustové štětce. Tyto obrázky se používají při vykreslování inkoustu s konkrétními hodnotami [`InkEffectType`](../inkeffecttype), jako jsou Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovlivnit, jak se každý inkoustový efekt zobrazuje. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný objekt, pokud neexistuje, a nastaví vlastnosti zástupného objektu na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní zástupný objekt (objekt z rozvržení a/nebo hlavního snímku, ze kterého je aktuální objekt odvozen). Vrací null, pokud aktuální objekt není odvozen. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu objektu. Typ hranic miniatury ShapeThumbnailBounds.Shape se používá jako výchozí. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu objektu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získává vizuální hranice objektu vypočítané z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento objekt není zástupný. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Ukládá obsah objektu jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Ukládá obsah objektu jako soubor SVG. |

### Viz také

* třída [GraphicalObject](../../aspose.slides/graphicalobject)
* rozhraní [IInk](../iink)
* jmenný prostor [Aspose.Slides.Ink](../../aspose.slides.ink)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->