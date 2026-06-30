---
title: LegacyDiagram
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje starszy obiekt diagramu.
type: docs
weight: 7650
url: /pl/aspose.slides/legacydiagram/
---
## LegacyDiagram klasa

Represents a legacy diagram object.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia alternatywny tekst powiązany z shape. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z shape. Odczyt/zapis String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Umożliwia pobranie podstawowego interfejsu IGraphicalObject. Tylko do odczytu [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak shape zostanie renderowany w trybie wyświetlania czarno-białego. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę punktów połączeń na shape. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca niestandardowe dane shape. Tylko do odczytu [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikseli zastosowane do shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości efektów. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości wypełnienia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki shape. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Zwraca blokady shape. Tylko do odczytu [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Zwraca lub ustawia wysokość shape, mierzona w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy shape jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżer hiperłączy. Tylko do odczytu [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Zwraca lub ustawia opcję 'Mark as decorative'. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy shape jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy shape jest TextHolder_PPT. Tylko do odczytu Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości linii. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę shape. Nie może być null. W razie potrzeby użyj pustego ciągu. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały okres życia shape i umożliwia PowerPointowi lub kodowi interop niezawodne odwołanie się do shape z dowolnego miejsca w dokumencie. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt GroupShape nadrzędny, jeśli shape jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla shape. Zwraca null, jeśli shape nie ma placeholdera. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki shape. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony shape jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny do ruchu wskazówek zegara. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Zwraca blokady shape. Tylko do odczytu [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 właściwości) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca slajd nadrzędny shape. Tylko do odczytu [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektów 3D dla shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości 3D. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może zostać zmieniona przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Zwraca lub ustawia szerokość shape, mierzona w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Zwraca lub ustawia współrzędną x lewego górnego rogu shape, mierzona w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Zwraca lub ustawia współrzędną y lewego górnego rogu shape, mierzona w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję shape w kolejności z-index. Shapes[0] zwraca shape znajdujący się z tyłu kolejności, a Shapes[Shapes.Count - 1] zwraca shape znajdujący się z przodu kolejności. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Konwertuje starszy diagram na edytowalny kształt grupowy. Utworzony obiekt GroupShape jest dodawany do nadrzędnego kształtu grupowego w tej samej pozycji. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Konwertuje starszy diagram na edytowalny obiekt SmartArt. Utworzony obiekt SmartArt jest dodawany do nadrzędnego kształtu grupowego w tej samej pozycji. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu nadrzędnego, z którego aktualny kształt jest dziedziczony). Zwraca null, jeśli aktualny kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę shape. Typ ograniczeń miniatury ShapeThumbnailBounds.Shape jest używany domyślnie. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Zwraca wizualne ograniczenia shape obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiuje, że ten shape nie jest placeholderem. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość Shape jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość Shape jako plik SVG. |

### Zobacz także

* klasa [GraphicalObject](../graphicalobject)
* interfejs [ILegacyDiagram](../ilegacydiagram)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->