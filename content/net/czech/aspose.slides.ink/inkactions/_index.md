---
title: InkActions
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje kořen ink akcí.
type: docs
weight: 7540
url: /cs/aspose.slides.ink/inkactions/
---
## InkActions třída

Represents the root of ink actions.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Číst/Zapisovat String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Číst/Zapisovat String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Číst/Zapisovat [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty použité na tvaru. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Číst/Zapisovat [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získává nebo nastavuje výšku tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Číst/Zapisovat Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Číst/Zapisovat [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Číst/Zapisovat [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získává nebo nastavuje možnost 'Mark as decorative'. Číst/Zapisovat Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Číst/Zapisovat String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací placeholder pro tvar. Vrací null, pokud tvar nemá žádný placeholder. Pouze pro čtení [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Číst/Zapisovat [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Číst/Zapisovat Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze pro čtení [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní, v rámci prezentace platný identifikátor určený pro použití doplňky nebo jiný kód. Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získává nebo nastavuje šířku tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získává nebo nastavuje x-souřadnici levého horního rohu tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získává nebo nastavuje y-souřadnici levého horního rohu tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru ve z-řadě. Shapes[0] vrací tvar na zadní pozici z-řady a Shapes[Shapes.Count - 1] vrací tvar na přední pozici z-řady. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní placeholder tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrací null, pokud aktuální tvar není zděděn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí typ použitého ohraničení miniatury je ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získává vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako SVG soubor. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako SVG soubor. |

### Viz také

* třída [GraphicalObject](../../aspose.slides/graphicalobject)
* rozhraní [IInkActions](../iinkactions)
* jmenný prostor [Aspose.Slides.Ink](../../aspose.slides.ink)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->