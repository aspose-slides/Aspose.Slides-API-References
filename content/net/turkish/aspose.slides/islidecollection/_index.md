---
title: ISlideCollection
second_title: Aspose.Sildes .NET için API Referansı
description: Slaytların bir koleksiyonunu temsil eder.
type: docs
weight: 7030
url: /tr/aspose.slides/islidecollection/
---
## ISlideCollection arabirimi

Slaytların bir koleksiyonunu temsil eder.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Belirtilen dizindeki öğeyi alır. Yalnız okunur [`ISlide`](../islide). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Belirtilen bir slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Belirtilen bir slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Belirtilen bir slaytın bir kopyasını belirtilen bölümün sonuna ekler. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Belirtilen bir kaynak slaytın bir kopyasını koleksiyonun sonuna ekler. Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaytın düzeniyle aynı Type veya Name’e sahip düzen olur). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Koleksiyonun sonuna yeni boş bir slayt ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini göz önünde bulundurarak bunları koleksiyonun sonuna ekler. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Belirtilen slaytın koleksiyondaki indeksini döndürür. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Belirtilen bir slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Belirtilen bir slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Belirtilen bir kaynak slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaytın düzeniyle aynı Type veya Name’e sahip düzen olur). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Belirtilen bir slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
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
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Koleksiyondan belirli bir nesnenin ilk örneğini kaldırır. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırayla indeks'ten başlayarak yerleştirilecektir. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. |

### Ayrıca Bakınız

* arabirim [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* arabirim [ISlide](../islide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->