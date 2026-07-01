---
title: ZoomFrame
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje objekt Slide Zoom na snímku.
type: docs
weight: 11820
url: /cs/aspose.slides/zoomframe/
---
## Třída ZoomFrame

Zastupuje objekt Slide Zoom na snímku.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Číst/Zapisovat String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Číst/Zapisovat String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Číst/Zapisovat [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti efektů. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Číst/Zapisovat [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Číst/Zapisovat Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Číst/Zapisovat [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Číst/Zapisovat [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Vrací nebo nastavuje typ obrázku zoom objektu. Číst/Zapisovat [`ZoomImageType`](../zoomimagetype). Výchozí hodnota: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Mark as decorative'. Číst/Zapisovat Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je to potřeba. Číst/Zapisovat String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Vrací null, pokud tvar nemá žádný zástupný prvek. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací rodičovskou prezentaci snímku. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Číst/Zapisovat [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Vrací nebo nastavuje chování navigace v prezentaci. Číst/Zapisovat Boolean. Výchozí hodnota: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Číst/Zapisovat Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 vlastnosti) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Vrací nebo nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Číst/Zapisovat Boolean. Výchozí hodnota: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací rodičovský snímek tvaru. Pouze pro čtení [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Vrací nebo nastavuje objekt snímku, na který odkazuje objekt Slide Zoom. Číst/Zapisovat [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Vrací nebo nastavuje dobu trvání přechodu mezi Zoom a snímkem. Číst/Zapisovat Single. Výchozí hodnota: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově přiřazena nově, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Číst/Zapisovat Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Vrací nebo nastavuje obrázek pro zoom objekt. Číst/Zapisovat [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-řazení. Shapes[0] vrací tvar na zadní pozici v z-řazení a Shapes[Shapes.Count - 1] vrací tvar na přední pozici v z-řazení. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na určený. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrací null, pokud aktuální tvar není zděděn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Ve výchozím nastavení se používá typ ShapeThumbnailBounds.Shape pro hranice miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Vrací vizuální hranice tvaru vypočítané z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [ZoomObject](../zoomobject)
* rozhraní [IZoomFrame](../izoomframe)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->