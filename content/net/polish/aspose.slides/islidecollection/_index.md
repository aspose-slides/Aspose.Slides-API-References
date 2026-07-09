---
title: ISlideCollection
second_title: Aspose.Sildes dla .NET – Dokumentacja API
description: Reprezentuje kolekcję slajdów.
type: docs
weight: 7050
url: /pl/aspose.slides/islidecollection/
---
## ISlideCollection interfejs

Represents a collection of a slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Pobiera element pod wskazanym indeksem. Tylko do odczytu [`ISlide`](../islide). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Dodaje kopię określonego slajdu na koniec określonej sekcji. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Dodaje kopię określonego slajdu źródłowego na koniec kolekcji. Odpowiedni układ zostanie automatycznie wybrany z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie istnieje odpowiedni układ, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Dodaje nowy pusty slajd na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Zwraca indeks określonego slajdu w kolekcji. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Wstawia kopię określonego slajdu w podaną pozycję w kolekcji. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Wstawia kopię określonego slajdu w podaną pozycję w kolekcji. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Wstawia kopię określonego slajdu źródłowego w podaną pozycję w kolekcji. Odpowiedni układ zostanie automatycznie wybrany z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie istnieje odpowiedni układ, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Wstawia kopię określonego slajdu w podaną pozycję w kolekcji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Usuwa element o podanym indeksie w kolekcji. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Przenosi slajd w kolekcji do podanej pozycji. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Przenosi slajdy w kolekcji do podanej pozycji. Slajdy będą umieszczane począwszy od indeksu w kolejności, w jakiej występują na liście. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Tworzy i zwraca tablicę zawierającą wszystkie slajdy. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Tworzy i zwraca tablicę zawierającą wszystkie slajdy z określonego zakresu. |

### Zobacz także

* interfejs [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfejs [ISlide](../islide)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->