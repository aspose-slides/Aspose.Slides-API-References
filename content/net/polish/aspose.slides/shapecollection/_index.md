---
title: ShapeCollection
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje kolekcję kształtów.
type: docs
weight: 9860
url: /pl/aspose.slides/shapecollection/
---
## ShapeCollection klasa

Reprezentuje kolekcję kształtów.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Zwraca liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). Tylko do odczytu Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Zwraca element pod określonym indeksem. Tylko do odczytu [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Zwraca obiekt grupowego kształtu nadrzędnego dla kolekcji kształtów. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Zwraca korzeń synchronizacji. Tylko do odczytu Object. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Tworzy nową ramkę audio powiązaną ze ścieżką CD i dodaje ją na koniec kolekcji kształtów. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Tworzy nowy automatyczny kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Tworzy nowy automatyczny kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjując go domyślnym formatowaniem szablonu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Tworzy nowy kształt łącznika z domyślnym stylizowaniem szablonu i dodaje go na koniec kolekcji kształtów. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylowanie szablonu. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Tworzy nowy pusty grupowy kształt i dodaje go na koniec kolekcji kształtów. Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie dodane do niej kształty. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Tworzy nowy grupowy kształt, konwertuje określony obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Tworzy nowy prostokątny automatyczny kształt przeznaczony do zawartości matematycznej i dodaje go na koniec kolekcji kształtów. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na koniec kolekcji kształtów. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Tworzy nową ramkę Section Zoom i dodaje ją na koniec kolekcji kształtów. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Tworzy nową ramkę Section Zoom z wstępnie określonym obrazem i dodaje ją na koniec kolekcji kształtów. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Usuwa wszystkie kształty z kolekcji kształtów. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Zwraca enumerator, który iteruje po kolekcji. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Zwraca indeks zero-bazowy pierwszego wystąpienia określonego kształtu w kolekcji. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Tworzy nową ramkę audio powiązaną ze ścieżką CD i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod podanym indeksem, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów pod podanym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Tworzy nowy automatyczny kształt i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne formatowanie szablonu. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Tworzy nowy automatyczny kształt i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie inicjując go domyślnym stylowaniem szablonu. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod podanym indeksem. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod podanym indeksem. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod podanym indeksem. Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod podanym indeksem. Nowy kształt zachowuje szerokość i wysokość *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne stylowanie szablonu. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie stosując domyślne stylowanie szablonu. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Tworzy nowy pusty grupowy kształt i wstawia go do kolekcji kształtów pod podanym indeksem. Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie dodane do niej kształty. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Tworzy nową ramkę Section Zoom z wstępnie określonym obrazem i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Tworzy nową ramkę Zoom z wstępnie określonym obrazem i wstawia ją do kolekcji kształtów pod podanym indeksem. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Usuwa kształt pod podanym indeksem z kolekcji kształtów. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Przenosi określony kształt do nowej pozycji w kolekcji kształtów. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Przenosi określone kształty w kolekcji kształtów, umieszczając je począwszy od podanego indeksu. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie. |

### Zobacz także

* klasa [DomObject&lt;TParent&gt;](../domobject-1)
* klasa [GroupShape](../groupshape)
* interfejs [IShapeCollection](../ishapecollection)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->