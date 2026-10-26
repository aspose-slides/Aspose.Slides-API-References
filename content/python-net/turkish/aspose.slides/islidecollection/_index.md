---
title: ISlideCollection class
second_title: Aspose.Slides için Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islidecollection/
---
## ISlideCollection sınıfı

Bir slayt koleksiyonunu temsil eder.

ISlideCollection türü aşağıdaki üyeleri gösterir:

Belirtilen indeksteki öğeyi alır.
            Salt okunur [`ISlide`](/slides/python-net/tr/aspose.slides/islide).

## Dizinleyici

| İsim | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/islidecollection/__getitem__/) |  |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/tr/aspose.slides/islidecollection/add_clone/#islide) | Belirtilen bir slaydın kopyasını koleksiyonun sonuna ekler. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/tr/aspose.slides/islidecollection/add_clone/#islide-isection) | Belirtilen bir slaydın kopyasını belirtilen bölümün sonuna ekler. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/tr/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Belirtilen bir slaydın kopyasını koleksiyonun sonuna ekler. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/tr/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Belirtilen bir kaynak slaydın kopyasını koleksiyonun sonuna ekler.<br/>            Uygun yerleşim, belirtilen <br/>            ana şablondan otomatik olarak seçilecektir (uygun yerleşim, kaynak slaydın yerleşimiyle aynı Tip veya İsim'e sahip yerleşimdir). Uygun bir yerleşim yoksa<br/>            kaynak slaydın yerleşimi kopyalanacaktır (eğer allowCloneMissingLayout <br/>            true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılacaktır. |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_clone/#int-islide) | Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Belirtilen bir kaynak slaydın kopyasını koleksiyonun belirtilen konumuna ekler.<br/>            Uygun yerleşim, belirtilen <br/>            ana şablondan otomatik olarak seçilecektir (uygun yerleşim, kaynak slaydın yerleşimiyle aynı Tip veya İsim'e sahip yerleşimdir). Uygun bir yerleşim yoksa<br/>            kaynak slaydın yerleşimi kopyalanacaktır (eğer allowCloneMissingLayout <br/>            true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılacaktır. |
| [`to_array(self)`](/slides/python-net/tr/aspose.slides/islidecollection/to_array/#) | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [`to_array(self, start_index, count)`](/slides/python-net/tr/aspose.slides/islidecollection/to_array/#int-int) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [`reorder(self, index, slide)`](/slides/python-net/tr/aspose.slides/islidecollection/reorder/#int-islide) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [`reorder(self, index, slides)`](/slides/python-net/tr/aspose.slides/islidecollection/reorder/#int-listislide) | Slaytları koleksiyondan belirtilen konuma taşır.<br/>            Slaytlar, listedeki göründükleri sıraya göre indeks itibarıyla yerleştirilecektir. |
| [`add_from_pdf(self, path)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_pdf/#str) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_text)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_html/#str) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_stream)`](/slides/python-net/tr/aspose.slides/islidecollection/add_from_html/#iorawiobase) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-str) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`add_empty_slide(self, layout)`](/slides/python-net/tr/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Yeni boş bir slaytı koleksiyonun sonuna ekler. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/tr/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`remove(self, value)`](/slides/python-net/tr/aspose.slides/islidecollection/remove/#islide) | Belirli bir nesnenin koleksiyondaki ilk görünümünü kaldırır. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/islidecollection/remove_at/#int) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [`index_of(self, slide)`](/slides/python-net/tr/aspose.slides/islidecollection/index_of/#islide) | Belirtilen slaydın koleksiyondaki indeksini döndürür. |


### Diğer Bilgiler
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)