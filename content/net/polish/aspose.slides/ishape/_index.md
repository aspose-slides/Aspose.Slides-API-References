---
title: IShape
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje kształt na slajdzie.
type: docs
weight: 6970
url: /pl/aspose.slides/ishape/
---
## interfejs IShape

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Zwraca lub ustawia tekst alternatywny powiązany z shape. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z shape. Odczyt/zapis String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Umożliwia pobranie podstawowego interfejsu IHyperlinkContainer. Tylko do odczytu [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Umożliwia pobranie podstawowego interfejsu ISlideComponent. Tylko do odczytu [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Właściwość określa, jak shape będzie renderowany w trybie wyświetlania czarno-białego. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Zwraca liczbę miejsc połączeń na shape. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Zwraca niestandardowe dane shape. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do shape. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla shape. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki shape. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Pobiera lub ustawia wysokość shape, mierzoną w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Określa, czy shape jest ukryty. Odczyt/zapis Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Pobiera lub ustawia opcję „Mark as decorative”. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Określa, czy shape jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Określa, czy shape jest TextHolder. Tylko do odczytu Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla shape. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Zwraca lub ustawia nazwę shape. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator o zakresie slajdu, który pozostaje stały przez cały czas życia shape i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do shape z dowolnego miejsca w dokumencie. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Zwraca obiekt GroupShape nadrzędny, jeśli shape jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Zwraca placeholder dla shape. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki shape. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony shape jest obrócony wokół osi z. Wartość dodatnia wskazuje obrót zgodny z ruchem wskazówek zegara; wartość ujemna wskazuje obrót przeciwny do ruchu wskazówek zegara. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Zwraca blokady shape. Tylko do odczytu [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości formatowania linii dla shape. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator o zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Pobiera lub ustawia szerokość shape, mierzoną w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Pobiera lub ustawia współrzędną x lewego górnego rogu shape, mierzoną w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Pobiera lub ustawia współrzędną y lewego górnego rogu shape, mierzoną w punktach. Odczyt/zapis Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Zwraca pozycję shape w kolejności z. Shapes[0] zwraca shape znajdujący się z tyłu kolejności z, a Shapes[Shapes.Count - 1] zwraca shape znajdujący się z przodu kolejności z. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholdera (shape z układu i/lub slajdu-matki, z którego dziedziczy bieżący shape). Zwraca null, jeśli bieżący shape nie jest dziedziczony. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Zwraca miniaturę shape. Typ ShapeThumbnailBounds.Shape jest używany domyślnie. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę shape. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiuje, że ten shape nie jest placeholderem. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Zapisuje zawartość Shape jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Zapisuje zawartość Shape jako plik SVG. |

### Zobacz także

* interfejs [IHyperlinkContainer](../ihyperlinkcontainer)
* interfejs [ISlideComponent](../islidecomponent)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->