---
title: IShapeCollection
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje kolekcję kształtów.
type: docs
weight: 7000
url: /pl/aspose.slides/ishapecollection/
---
## IShapeCollection interfejs

Reprezentuje kolekcję kształtów.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Pobiera element pod określonym indeksem. Tylko do odczytu [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Pobiera obiekt nadrzędnego grupowego kształtu dla kolekcji kształtów. Tylko do odczytu [`IGroupShape`](../igroupshape). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i dodaje ją na koniec kolekcji kształtów. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Skopiowany kształt zachowuje pozycję i rozmiar oryginału. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Tworzy nowy łącznikowy kształt z domyślnym stylizowaniem szablonu i dodaje go na koniec kolekcji kształtów. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Tworzy nowy łącznikowy kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylizowanie szablonu. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Tworzy nowy pusty grupowy kształt i dodaje go na koniec kolekcji kształtów. Ramka grupy będzie automatycznie dopasowywać się do dodanych do niej kształtów. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Tworzy nowy grupowy kształt, konwertuje podany obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Tworzy nowy prostokątny auto-kształt do hostowania treści matematycznej i dodaje go na koniec kolekcji kształtów. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Tworzy nową ramkę obrazu zawierającą podany obraz i dodaje ją na koniec kolekcji kształtów. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Tworzy nową ramkę Section Zoom i dodaje ją na koniec kolekcji kształtów. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Tworzy nową ramkę Section Zoom z wcześniej określonym obrazem i dodaje ją na koniec kolekcji kształtów. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Usuwa wszystkie kształty z kolekcji kształtów. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Zwraca indeks (zerowy) pierwszego wystąpienia określonego kształtu w kolekcji. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod podanym indeksem, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów pod podanym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne formatowanie szablonu. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie inicjalizując go domyślnym stylizowaniem szablonu. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod podanym indeksem. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod podanym indeksem. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod podanym indeksem. Skopiowany kształt zachowuje pozycję i rozmiar oryginału. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod podanym indeksem. Nowy kształt zachowuje szerokość i wysokość *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Tworzy nowy łącznikowy kształt i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne stylizowanie szablonu. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Tworzy nowy łącznikowy kształt i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie stosując domyślne stylizowanie szablonu. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Tworzy nowy pusty grupowy kształt i wstawia go do kolekcji kształtów pod podanym indeksem. Ramka grupy będzie automatycznie dopasowywać się do dodanych do niej kształtów. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Tworzy nową ramkę obrazu zawierającą podany obraz i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Tworzy nową ramkę Section Zoom z wcześniej określonym obrazem i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Tworzy nową ramkę Zoom z wcześniej określonym obrazem i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Usuwa kształt pod podanym indeksem z kolekcji kształtów. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Przenosi określony kształt do nowej pozycji w kolekcji kształtów. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Przenosi określone kształty w kolekcji kształtów, umieszczając je zaczynając od podanego indeksu. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w podanym zakresie. |

### Zobacz także

* interfejs [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfejs [IShape](../ishape)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->