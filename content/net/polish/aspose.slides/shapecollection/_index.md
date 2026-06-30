---
title: ShapeCollection
second_title: Aspose.Sildes dla referencji API .NET
description: Reprezentuje kolekcję kształtów.
type: docs
weight: 9840
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
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). Tylko do odczytu Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Zwraca element o podanym indeksie. Tylko do odczytu [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Zwraca obiekt nadrzędnego grupowego kształtu dla kolekcji kształtów. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Zwraca korzeń synchronizacji. Tylko do odczytu Object. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i dodaje ją na końcu kolekcji kształtów. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Tworzy nową ramkę audio i dodaje ją na końcu kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Tworzy nową ramkę audio z wbudowanym plikiem WAV i dodaje ją na końcu kolekcji kształtów. Wbudowane audio jest dodawane do kolekcji Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na końcu kolekcji kształtów. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Tworzy nowy kształt automatyczny z domyślnym formatowaniem i dodaje go na końcu kolekcji kształtów. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Tworzy nowy kształt automatyczny i dodaje go na końcu kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, i dodaje go na końcu kolekcji kształtów. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, i dodaje go na końcu kolekcji kształtów. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Tworzy kopię określonego kształtu i dodaje ją na końcu kolekcji kształtów. Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Tworzy kopię określonego kształtu i dodaje ją na końcu kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Tworzy kopię określonego kształtu i dodaje ją na końcu kolekcji kształtów. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Tworzy nowy kształt łącznika z domyślnym stylizowaniem szablonu i dodaje go na końcu kolekcji kształtów. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Tworzy nowy kształt łącznika i dodaje go na końcu kolekcji kształtów, opcjonalnie stosując domyślne stylowanie szablonu. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Tworzy nowy pusty kształt grupy i dodaje go na końcu kolekcji kształtów. Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie dodane do niej kształty. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Tworzy nowy kształt grupy, konwertuje określony obraz SVG na indywidualne kształty i dodaje powstałą grupę na końcu kolekcji kształtów. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Tworzy nowy prostokątny kształt automatyczny przeznaczony do treści matematycznej i dodaje go na końcu kolekcji kształtów. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Tworzy nową ramkę obiektu OLE i dodaje ją na końcu kolekcji kształtów. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Tworzy nową ramkę obiektu OLE i dodaje ją na końcu kolekcji kształtów. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na końcu kolekcji kształtów. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Tworzy nową ramkę Section Zoom i dodaje ją na końcu kolekcji kształtów. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Tworzy nową ramkę Section Zoom z predefiniowanym obrazem i dodaje ją na końcu kolekcji kształtów. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Tworzy diagram SmartArt i dodaje go na końcu kolekcji kształtów. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Tworzy nową ramkę Summary Zoom i dodaje ją na końcu kolekcji kształtów. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Tworzy nową tabelę i dodaje ją na końcu kolekcji kształtów. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Tworzy nową ramkę wideo i dodaje ją na końcu kolekcji kształtów. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Tworzy nową ramkę wideo i dodaje ją na końcu kolekcji kształtów. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Tworzy nową ramkę Zoom i dodaje ją na końcu kolekcji kształtów. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Tworzy nową ramkę Zoom i dodaje ją na końcu kolekcji kształtów. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Usuwa wszystkie kształty z kolekcji kształtów. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Zwraca enumerator, który iteruje po kolekcji. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Zwraca indeks zerowy pierwszego wystąpienia określonego kształtu w kolekcji. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod określonym indeksem, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Tworzy nową ramkę audio z wbudowanym plikiem WAV i wstawia ją do kolekcji kształtów pod określonym indeksem. Wbudowane audio jest dodawane do kolekcji Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod określonym indeksem, stosując domyślne formatowanie szablonu. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod określonym indeksem, opcjonalnie inicjalizując go domyślnym stylowaniem szablonu. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, i wstawia go do kolekcji kształtów pod określonym indeksem. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, i wstawia go do kolekcji kształtów pod określonym indeksem. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem. Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem. Nowy kształt zachowuje szerokość i wysokość *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem, stosując domyślne stylowanie szablonu. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem, opcjonalnie stosując domyślne stylowanie szablonu. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Tworzy nowy pusty kształt grupy i wstawia go do kolekcji kształtów pod określonym indeksem. Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie dodane do niej kształty. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Tworzy nową ramkę Section Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Usuwa kształt pod określonym indeksem z kolekcji kształtów. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Przenosi określony kształt na nową pozycję w kolekcji kształtów. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Przenosi określone kształty w kolekcji kształtów, umieszczając je zaczynając od podanego indeksu. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie. |

### Zobacz także

* klasa [DomObject&lt;TParent&gt;](../domobject-1)
* klasa [GroupShape](../groupshape)
* interfejs [IShapeCollection](../ishapecollection)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->