---
title: SlideCollection
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje kolekcję slajdów.
type: docs
weight: 9950
url: /pl/aspose.slides/slidecollection/
---
## SlideCollection klasa

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Zwraca element o określonym indeksie. Tylko do odczytu [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Zwraca korzeń synchronizacji. Tylko do odczytu Object. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Dodaje kopię określonego slajdu na koniec określonej sekcji. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Dodaje kopię określonego slajdu źródłowego na koniec kolekcji. Odpowiedni układ zostanie wybrany automatycznie z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Dodaje nowy pusty slajd na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Zwraca enumerator, który iteruje po kolekcji. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Zwraca indeks określonego slajdu w kolekcji. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Wstawia kopię określonego slajdu na podane miejsce w kolekcji. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Wstawia kopię określonego slajdu na podane miejsce w kolekcji. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Wstawia kopię określonego slajdu źródłowego na podane miejsce w kolekcji. Odpowiedni układ zostanie wybrany automatycznie z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Wstawia kopię określonego slajdu na podane miejsce w kolekcji. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanym miejscu. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Usuwa element o podanym indeksie z kolekcji. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Przenosi slajd w kolekcji na podane miejsce. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Przenosi slajdy w kolekcji na podane miejsce. Slajdy będą umieszczane począwszy od indeksu w kolejności, w jakiej występują na liście. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Tworzy i zwraca tablicę zawierającą wszystkie slajdy. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Tworzy i zwraca tablicę zawierającą wszystkie slajdy z określonego zakresu. Indeks pierwszego slajdu do dodania. Liczba slajdów do dodania. |

### Patrz także

* klasa [DomObject&lt;TParent&gt;](../domobject-1)
* klasa [Presentation](../presentation)
* interfejs [ISlideCollection](../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->