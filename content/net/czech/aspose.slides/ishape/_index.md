---
title: IShape
second_title: Aspose.Sildes pro .NET API reference
description: Reprezentuje tvar na snímku.
type: docs
weight: 6930
url: /cs/aspose.slides/ishape/
---
## IShape rozhraní

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem. Čtení/Zápis String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Umožňuje získat základní rozhraní IHyperlinkContainer. Pouze ke čtení [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Umožňuje získat základní rozhraní ISlideComponent. Pouze ke čtení [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze ke čtení Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Vrací vlastní data tvaru. Pouze ke čtení [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Pouze ke čtení [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Pouze ke čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/Zápis Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Označit jako dekorativní'. Čtení/Zápis Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze ke čtení Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Určuje, zda je tvar TextHolder. Pouze ke čtení Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Pouze ke čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Čtení/Zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar z libovolného místa v dokumentu. Pouze ke čtení UInt32. Viz také [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Vrací nadřazený objekt GroupShape, pokud je tvar seskupený. Jinak vrací null. Pouze ke čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Pouze ke čtení [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Vrací zámky tvaru. Pouze ke čtení [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje vlastnosti formátování čáry pro tvar. Pouze ke čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přenastavit, nesmí být považována za trvalý jedinečný klíč. Pouze ke čtení UInt32. Viz také [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Vrací pozici tvaru ve z-řazení. Shapes[0] vrací tvar na konci z-řazení a Shapes[Shapes.Count - 1] vrací tvar na začátku z-řazení. Pouze ke čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímky, ze kterého je aktuální tvar zděděn). Pokud aktuální tvar není zděděn, vrátí null. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Vrací miniaturu tvaru. Typ ohraničení miniatury ShapeThumbnailBounds.Shape se používá ve výchozím nastavení. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* rozhraní [IHyperlinkContainer](../ihyperlinkcontainer)
* rozhraní [ISlideComponent](../islidecomponent)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->