---
title: IShape
second_title: Aspose.Sildes for .NET – Dokumentacja API
description: Reprezentuje kształt na slajdzie.
type: docs
weight: 6950
url: /pl/aspose.slides/ishape/
---
## IShape interfejs

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt/zapis String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Umożliwia pobranie bazowego interfejsu IHyperlinkContainer. Tylko do odczytu [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Umożliwia pobranie bazowego interfejsu ISlideComponent. Tylko do odczytu [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Określa, jak kształt będzie renderowany w trybie czarno-białym. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Zwraca liczbę miejsc połączeń na kształcie. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Zwraca dane niestandardowe kształtu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Pobiera lub ustawia wysokość kształtu wyrażoną w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Pobiera lub ustawia opcję „Mark as decorative”. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Określa, czy kształt jest TextHolder. Tylko do odczytu Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator w obrębie slajdu, który pozostaje niezmienny przez cały czas życia kształtu i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca dokumentu. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Zwraca placeholder dla kształtu. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Zwraca obiekt ThreeDFormat zawierający właściwości formatowania linii dla kształtu. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator w obrębie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być zmieniona przez użytkownika lub programowo, nie należy traktować jej jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Pobiera lub ustawia szerokość kształtu wyrażoną w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu wyrażoną w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu wyrażoną w punktach. Odczyt/zapis Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt na przedzie kolejności Z. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go brak i ustawia właściwości placeholdera na określony. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholdera (k shape z układu i/lub slajdu głównego, z którego aktualny kształt został odziedziczony). Null jest zwracany, jeśli aktualny kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Zwraca miniaturę kształtu. Typ ShapeThumbnailBounds.Shape dla granic miniatury kształtu jest używany domyślnie. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę kształtu. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiuje, że ten kształt nie jest placeholderem. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Zapisuje zawartość kształtu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Zapisuje zawartość kształtu jako plik SVG. |

### Zobacz także

* interfejs [IHyperlinkContainer](../ihyperlinkcontainer)
* interfejs [ISlideComponent](../islidecomponent)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->