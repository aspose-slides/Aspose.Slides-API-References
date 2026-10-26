---
title: SlideCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slidecollection/
---
## SlideCollection sınıfı

Slaytların bir koleksiyonunu temsil eder.

SlideCollection türü aşağıdaki üyeleri sunar:

Belirtilen dizindeki öğeyi alır.
            Sadece okuma [`Slide`](/slides/python-net/tr/aspose.slides/slide).

## İndeksleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/slidecollection/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/tr/aspose.slides/slidecollection/add_clone/#islide) | Belirtilen bir slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/tr/aspose.slides/slidecollection/add_clone/#islide-isection) | Belirtilen bir slaydın bir kopyasını belirtilen bölümün sonuna ekler. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/tr/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Belirtilen bir slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/tr/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Belirtilen bir kaynak slaydının bir kopyasını koleksiyonun sonuna ekler.<br/>            Uygun düzen, belirtilen master'dan otomatik olarak seçilecektir (uygun düzen, kaynak slaydın düzeniyle aynı Type veya Name'e sahip düzenidir). Uygun bir düzen bulunmazsa<br/>            kaynak slaydın düzeni kopyalanacaktır (eğer allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılacaktır. |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_clone/#int-islide) | Belirtilen bir slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Belirtilen bir slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Belirtilen bir kaynak slaydının bir kopyasını koleksiyonun belirtilen konumuna ekler.<br/>            Uygun düzen, belirtilen master'dan otomatik olarak seçilecektir (uygun düzen, kaynak slaydın düzeniyle aynı Type veya Name'e sahip düzenidir). Uygun bir düzen bulunmazsa<br/>            kaynak slaydın düzeni kopyalanacaktır (eğer allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılacaktır. |
| [`to_array(self)`](/slides/python-net/tr/aspose.slides/slidecollection/to_array/#) | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [`to_array(self, start_index, count)`](/slides/python-net/tr/aspose.slides/slidecollection/to_array/#int-int) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür.<br/>            Eklenmek üzere ilk slaydın indeksi. Eklenmek üzere slayt sayısı. |
| [`reorder(self, index, slide)`](/slides/python-net/tr/aspose.slides/slidecollection/reorder/#int-islide) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [`reorder(self, index, slides)`](/slides/python-net/tr/aspose.slides/slidecollection/reorder/#int-listislide) | Slaytları koleksiyondan belirtilen konuma taşır.<br/>            Slaytlar, listedeki göründükleri sırayla indeks'ten itibaren yerleştirilecektir. |
| [`add_from_pdf(self, path)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_pdf/#str) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini göz önünde bulundurarak koleksiyonun sonuna ekler. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_text)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_html/#str) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`add_from_html(self, html_stream)`](/slides/python-net/tr/aspose.slides/slidecollection/add_from_html/#iorawiobase) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-str) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [`add_empty_slide(self, layout)`](/slides/python-net/tr/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Koleksiyonun sonuna yeni boş bir slayt ekler. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/tr/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Belirtilen bir slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`remove(self, value)`](/slides/python-net/tr/aspose.slides/slidecollection/remove/#islide) | Belirli bir nesnenin koleksiyondaki ilk görünümünü kaldırır. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/slidecollection/remove_at/#int) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [`index_of(self, slide)`](/slides/python-net/tr/aspose.slides/slidecollection/index_of/#islide) | Koleksiyondaki belirtilen slaydın indeksini döndürür. |

### Ayrıca Bakınız
* sınıf [`Slide`](/slides/python-net/tr/aspose.slides/slide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kitaplık [`Aspose.Slides`](/slides/python-net)