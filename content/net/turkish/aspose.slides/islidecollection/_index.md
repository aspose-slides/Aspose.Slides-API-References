---
title: ISlideCollection
second_title: Aspose.Sildes .NET API Referansı
description: Slaytların bir koleksiyonunu temsil eder.
type: docs
weight: 7050
url: /tr/aspose.slides/islidecollection/
---
## ISlideCollection arayüz

Bir slayt koleksiyonunu temsil eder.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Belirtilen indeksdeki öğeyi alır. Salt okunur [`ISlide`](../islide). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Belirtilen slaytın bir kopyasını belirtilen bölümün sonuna ekler. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Belirtilen kaynak slaytın bir kopyasını koleksiyonun sonuna ekler. Uygun düzen, belirtilen ana master'dan otomatik olarak seçilecektir (uygun düzen, kaynak slaytın düzeniyle aynı Type veya Name'e sahip düzen olur). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Yeni boş bir slaytı koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Koleksiyondaki belirtilen slaytın indeksini döndürür. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Belirtilen kaynak slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. Uygun düzen, belirtilen ana master'dan otomatik olarak seçilecektir (uygun düzen, kaynak slaytın düzeniyle aynı Type veya Name'e sahip düzen olur). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonda belirtilen konuma ekler. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırada indeks'ten itibaren yerleştirilecektir. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. |

### Ayrıca Bakınız

* arayüz [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* arayüz [ISlide](../islide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->