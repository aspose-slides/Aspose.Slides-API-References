---
title: SlideCollection
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayt koleksiyonunu temsil eder.
type: docs
weight: 9970
url: /tr/aspose.slides/slidecollection/
---
## SlideCollection sınıfı

Bir slayt koleksiyonunu temsil eder.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Koleksiyonda gerçekte bulunan eleman sayısını alır. Yalnızca okuma Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Koleksiyona erişimin eşzamanlı (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Belirtilen dizindeki öğeyi alır. Yalnızca okuma [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Bir eşzamanlama kökü döndürür. Yalnızca okuma Object. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Belirtilen slaytın bir kopyasını belirtilen bölümün sonuna ekler. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Belirtilen kaynak slaytın bir kopyasını koleksiyonun sonuna ekler. Uygun düzen, belirtilen masterdan otomatik olarak seçilir (uygun düzen, kaynak slaytın düzeniyle aynı Type veya Name değerine sahip düzenlerdir). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Koleksiyonun sonuna yeni boş bir slayt ekler. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Koleksiyon üzerinden yineleme yapan bir enumerator döndürür. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Belirtilen slaytın koleksiyondaki dizinini döndürür. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Belirtilen kaynak slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. Uygun düzen, belirtilen masterdan otomatik olarak seçilir (uygun düzen, kaynak slaytın düzeniyle aynı Type veya Name değerine sahip düzenlerdir). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML metninden slaytlar oluşturur ve bunları koleksiyonun belirtilen konumuna ekler. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Koleksiyondaki belirtilen dizindeki öğeyi kaldırır. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISSlide[]) | Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırayla indeksden itibaren yerleştirilecektir. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. Eklenecek ilk slaytın indeksi. Eklenecek slayt sayısı. |

### Ayrıca Bakınız

* sınıf [DomObject&lt;TParent&gt;](../domobject-1)
* sınıf [Presentation](../presentation)
* arayüz [ISlideCollection](../islidecollection)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->