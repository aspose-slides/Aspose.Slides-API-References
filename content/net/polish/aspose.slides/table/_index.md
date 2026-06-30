---
title: Table
second_title: Odwołanie API Aspose.Sildes dla .NET
description: Reprezentuje tabelę na slajdzie.
type: docs
weight: 10840
url: /pl/aspose.slides/table/
---
## Table klasa

Represents a table on a slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Właściwości

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia tekst alternatywny powiązany z obiektem shape. Odczyt/Zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z obiektem shape. Odczyt/Zapis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak obiekt shape będzie renderowany w trybie czarno-białym. Odczyt/Zapis [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Zwraca kolekcję kolumn. Tylko do odczytu [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę punktów połączeń w obiekcie shape. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca niestandardowe dane obiektu shape. Tylko do odczytu [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikseli zastosowane do obiektu shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości efektu. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Zwraca obiekt TableFormat.FillFormat zawierający formatowanie wypełnienia dla Table. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Odczyt/Zapis Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Odczyt/Zapis Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki shape. Odczyt/Zapis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Zwraca blokady shape. Tylko do odczytu [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Zwraca lub ustawia wysokość shape, mierzona w punktach. Odczyt/Zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy shape jest ukryty. Odczyt/Zapis Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Odczyt/Zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą. Odczyt/Zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżer hiperłączy. Tylko do odczytu [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/Zapis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Zwraca lub ustawia opcję 'Mark as decorative'. Odczyt/Zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy shape jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy shape jest TextHolder_PPT. Tylko do odczytu Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Zwraca komórkę o podanych indeksach kolumny i wiersza. Tylko do odczytu [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Odczyt/Zapis Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Odczyt/Zapis Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości linii. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę shape. Nie może być null. W razie potrzeby użyj pustego ciągu znaków. Odczyt/Zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia shape i umożliwia PowerPointowi lub kodowi interop wiarygodne odwoływanie się do shape z dowolnego miejsca dokumentu. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt nadrzędny GroupShape, jeśli shape jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla shape. Zwraca null, jeśli shape nie ma placeholdera. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca nadrzędną prezentację slajdu. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki shape. Odczyt/Zapis [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Określa, czy tabela ma kolejność czytania od prawej do lewej. Odczyt/Zapis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony shape jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna – przeciwny. Odczyt/Zapis Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Zwraca kolekcję wierszy. Tylko do odczytu [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Zwraca blokady shape. Tylko do odczytu [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 właściwości) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca nadrzędny slajd shape. Tylko do odczytu [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Zwraca lub ustawia wbudowany styl tabeli. Odczyt/Zapis [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Zwraca obiekt TableFormat zawierający właściwości formatowania tej tabeli. Tylko do odczytu [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla shape. Uwaga: może zwrócić null dla niektórych typów shape, które nie mają właściwości 3D. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Odczyt/Zapis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Zwraca lub ustawia szerokość shape, mierzona w punktach. Odczyt/Zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Zwraca lub ustawia współrzędną x lewego górnego rogu shape, mierzona w punktach. Odczyt/Zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Zwraca lub ustawia współrzędną y lewego górnego rogu shape, mierzona w punktach. Odczyt/Zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję shape w kolejności z-order. Shapes[0] zwraca shape znajdujący się najdalej w tle, a Shapes[Shapes.Count - 1] zwraca shape znajdujący się na samym wierzchu. Tylko do odczytu Int32. |

## Metody

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli nie istnieje, i ustawia właściwości placeholdera na określony. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy placeholder (shape z układu i/lub slajdu master, z którego dziedziczy aktualny shape). Null jest zwracany, jeśli aktualny shape nie dziedziczy. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę shape. Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Zwraca wizualne granice shape obliczone na podstawie jego renderowanej zawartości. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Scali sąsiadujące komórki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Określa, że ten shape nie jest placeholderem. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Ustawia określone właściwości formatu akapitu dla wszystkich akapitów w komórkach tabeli. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Ustawia określone właściwości formatu fragmentu dla wszystkich fragmentów w komórkach tabeli. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Ustawia określone właściwości formatu ramki tekstowej dla wszystkich ramek tekstowych w komórkach tabeli. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość Shape jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość Shape jako plik SVG. |

### Zobacz także

* klasa [GraphicalObject](../graphicalobject)
* interfejs [ITable](../itable)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->