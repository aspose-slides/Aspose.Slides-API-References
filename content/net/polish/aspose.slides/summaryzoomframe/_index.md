---
title: SummaryZoomFrame
second_title: Aspose.Sildes dla Dokumentacji API .NET
description: Reprezentuje obiekt Summary Zoom na slajdzie.
type: docs
weight: 10750
url: /pl/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame klasa

Reprezentuje obiekt Summary Zoom na slajdzie.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## Właściwości

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia alternatywny tekst powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem. Odczyt/zapis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym wyświetlania. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę miejsc połączeń na kształcie. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca niestandardowe dane kształtu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektów. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości wypełnienia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Pobiera lub ustawia wysokość kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżera hiperłączy. Tylko do odczytu [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Pobiera lub ustawia opcję "Oznacz jako dekoracyjne". Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | Pobiera układ sekcji Summary Zoom w ramce. Domyślna wartość to GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego łańcucha. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator przypisany do slajdu, który pozostaje stały przez cały czas życia kształtu i pozwala PowerPointowi lub kodowi interop wiarygodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt nadrzędnego GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca nadrzędną prezentację slajdu. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót w prawo (zgodnie z ruchem wskazówek zegara), a ujemna obrót w lewo (przeciwnie do ruchu wskazówek zegara). Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 właściwości) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca nadrzędny slajd kształtu. Tylko do odczytu [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | Pobiera [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) dla obiektu Summary Zoom Frame. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator przypisany do prezentacji, przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być zmieniona przez użytkownika lub programowo, nie należy traktować jej jako trwałego unikalnego klucza. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Pobiera lub ustawia szerokość kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Pobiera lub ustawia współrzędną x lewego górnego narożnika kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Pobiera lub ustawia współrzędną y lewego górnego narożnika kształtu, mierzona w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się najdalej na końcu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się najbliżej przodu kolejności Z. Tylko do odczytu Int32. |

## Metody

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu-mistrza, z którego dziedziczy bieżący kształt). Zwraca null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę kształtu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiuje, że ten kształt nie jest placeholderem. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość kształtu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość kształtu jako plik SVG. |

### Zobacz także

* klasa [GraphicalObject](../graphicalobject)
* interfejs [ISummaryZoomFrame](../isummaryzoomframe)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->