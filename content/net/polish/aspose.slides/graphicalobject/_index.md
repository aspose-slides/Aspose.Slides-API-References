---
title: GraphicalObject
second_title: Aspose.Slides dla .NET – odniesienie API
description: Reprezentuje abstrakcyjny obiekt graficzny.
type: docs
weight: 5050
url: /pl/aspose.slides/graphicalobject/
---
## GraphicalObject klasa

Reprezentuje abstrakcyjny obiekt graficzny.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt/zapis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę miejsc połączeń na kształcie. Tylko odczyt Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca dane niestandardowe kształtu. Tylko odczyt [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektów. Tylko odczyt [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości wypełnienia. Tylko odczyt [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Zwraca blokady kształtu. Tylko odczyt [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Zwraca lub ustawia wysokość kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżera hiperłączy. Tylko odczyt [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Zwraca lub ustawia opcję 'Mark as decorative'. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko odczyt Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy kształt jest TextHolder_PPT. Tylko odczyt Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko odczyt [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu znaków. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator ograniczony do slajdu, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPoint lub kodowi interop wiarygodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. Tylko odczyt UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko odczyt [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko odczyt [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca prezentację nadrzędną slajdu. Tylko odczyt [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny do ruchu wskazówek zegara. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Zwraca blokady kształtu. Tylko odczyt [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 właściwości) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca slajd nadrzędny kształtu. Tylko odczyt [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektów 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko odczyt [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator ograniczony do prezentacji, przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko odczyt UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Zwraca lub ustawia szerokość kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Zwraca lub ustawia współrzędną x lewego górnego rogu kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Zwraca lub ustawia współrzędną y lewego górnego rogu kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z. Tylko odczyt Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu nadrzędnego, z którego dziedziczy bieżący kształt). Zwraca null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę kształtu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Zwraca wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiuje, że ten kształt nie jest placeholderem. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość kształtu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość kształtu jako plik SVG. |

### Zobacz także

* klasa [Shape](../shape)
* interfejs [IGraphicalObject](../igraphicalobject)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->