---
title: IShape
second_title: Aspose.Sildes pro .NET API referenci
description: Reprezentuje tvar na snímku.
type: docs
weight: 6950
url: /cs/aspose.slides/ishape/
---
## IShape rozhraní

Reprezentuje tvar na snímku.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem. Čtení/Zápis String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Umožňuje získat základní rozhraní IHyperlinkContainer. Pouze pro čtení [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Umožňuje získat základní rozhraní ISlideComponent. Pouze pro čtení [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Vlastnost určuje, jak se tvar vykreslí v režimu černobílého zobrazení. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/Zápis Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Označit jako dekorativní'. Čtení/Zápis Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Určuje, zda je tvar TextHolder. Pouze pro čtení Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Čtení/Zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rozsahu snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje aplikaci PowerPoint nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Vrací objekt rodičovského GroupShape, pokud je tvar seskupen. V opačném případě vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy z. Kladná hodnota znamená otáčení ve směru hodinových ručiček; záporná hodnota znamená otáčení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Vrací interní identifikátor v rozsahu prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově přidělena znovu, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Vrací pozici tvaru v z-pořadí. Shapes[0] vrací tvar na pozadí z-pořadí a Shapes[Shapes.Count - 1] vrací tvar v popředí z-pořadí. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na určený. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen). Pokud aktuální tvar není odvozen, vrátí se null. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Vrací miniaturu tvaru. Typ ohraničení miniatury ShapeThumbnailBounds.Shape se používá jako výchozí. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Určuje, že tento tvar není zástupný prvek. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* rozhraní [IHyperlinkContainer](../ihyperlinkcontainer)
* rozhraní [ISlideComponent](../islidecomponent)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->