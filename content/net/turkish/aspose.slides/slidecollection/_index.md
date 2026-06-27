---
title: SlideCollection
second_title: Aspose.Sildes .NET API Referansı
description: Bir slayt koleksiyonunu temsil eder.
type: docs
weight: 9950
url: /tr/aspose.slides/slidecollection/
---
## SlideCollection sınıfı

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Koleksiyonda gerçekte bulunan öğe sayısını alır. Salt okunur Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Belirtilen indeksteki öğeyi alır. Salt okunur [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Bir senkronizasyon kökü döndürür. Salt okunur Object. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Belirtilen bir slaytın kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Belirtilen bir slaytın kopyasını koleksiyonun sonuna ekler. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Belirtilen bir slaytın kopyasını belirtilen bölümün sonuna ekler. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Belirtilen bir kaynak slaytın kopyasını koleksiyonun sonuna ekler. Uygun yerleşim, belirtilen masterdan otomatik olarak seçilir (uygun yerleşim, kaynak slaytın yerleşimiyle aynı Type veya Name değerine sahip yerleşimdir). Eğer uygun bir yerleşim yoksa, kaynak slaytın yerleşimi klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
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
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF belgesinden slaytlar oluşturur ve pdf içe aktarım seçeneklerini dikkate alarak koleksiyonun sonuna ekler. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Belirtilen slaytın koleksiyondaki indeksini döndürür. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Belirtilen bir slaytın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Belirtilen bir slaytın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Belirtilen bir kaynak slaytın kopyasını koleksiyonun belirtilen konumuna ekler. Uygun yerleşim, belirtilen masterdan otomatik olarak seçilir (uygun yerleşim, kaynak slaytın yerleşimiyle aynı Type veya Name değerine sahip yerleşimdir). Eğer uygun bir yerleşim yoksa, kaynak slaytın yerleşimi klonlanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Belirtilen bir slaytın kopyasını koleksiyonun belirtilen konumuna ekler. |
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
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Belirli bir nesnenin koleksiyondaki ilk görünümünü kaldırır. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar listede göründükleri sırayla indeksten başlayarak yerleştirilecektir. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. İlk eklenecek slaytın indeksi. Eklenecek slayt sayısı. |

### Ayrıca Bakınız

* sınıf [DomObject&lt;TParent&gt;](../domobject-1)
* sınıf [Presentation](../presentation)
* arayüz [ISlideCollection](../islidecollection)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->