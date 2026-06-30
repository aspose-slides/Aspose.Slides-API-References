---
title: IShape
second_title: Aspose.Sildes dla .NET - odniesienie API
description: Reprezentuje kształt na slajdzie.
type: docs
weight: 6930
url: /pl/aspose.slides/ishape/
---
## interfejs IShape

Reprezentuje kształt na slajdzie.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Właściwości

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Zwraca lub ustawia alternatywny tekst powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem. Odczyt/zapis String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Umożliwia uzyskanie podstawowego interfejsu IHyperlinkContainer. Tylko do odczytu [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Umożliwia uzyskanie podstawowego interfejsu ISlideComponent. Tylko do odczytu [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Zwraca liczbę miejsc połączeń na kształcie. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Zwraca niestandardowe dane kształtu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Zwraca lub ustawia wysokość kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Zwraca lub ustawia opcję 'Mark as decorative'. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Określa, czy kształt jest TextHolder. Tylko do odczytu Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Zwraca symbol zastępczy dla kształtu. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość tę może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Zwraca lub ustawia szerokość kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Zwraca lub ustawia współrzędną x lewego górnego narożnika kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Zwraca lub ustawia współrzędną y lewego górnego narożnika kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z. Tylko do odczytu Int32. |

## Metody

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Dodaje nowy symbol zastępczy, jeśli go nie ma, i ustawia właściwości symbolu zastępczego na określony. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Zwraca podstawowy kształt symbolu zastępczego (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt). Zwracane jest null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę kształtu. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiuje, że ten kształt nie jest symbolem zastępczym. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Zapisuje zawartość kształtu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Zapisuje zawartość kształtu jako plik SVG. |

### Zobacz także

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->