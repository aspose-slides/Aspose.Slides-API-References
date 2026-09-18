---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/
---
## ShapeCollection sınıfı

Şekillerin bir koleksiyonunu temsil eder.

ShapeCollection türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`parent_group`](/slides/python-net/tr/aspose.slides/shapecollection/parent_group/) | Şekil koleksiyonu için üst grup şekil nesnesini alır.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |

Belirtilen indeksteki öğeyi alır.
            Salt-okunur [`IShape`](/slides/python-net/tr/aspose.slides/ishape).

## Dizinleyici

| İsim | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/shapecollection/__getitem__/) |  |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve<br/>            şekil koleksiyonunun sonuna ekler. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/tr/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve<br/>            şekil koleksiyonunun sonuna ekler. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır,<br/>            ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır,<br/>            ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/tr/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/tr/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Yeni bir Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Önceden tanımlı bir görselle yeni bir Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/tr/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Yeni bir Bölüm Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/tr/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Önceden tanımlı bir görselle yeni bir Bölüm Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Yeni bir Bölüm Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Önceden tanımlı bir görselle yeni bir Bölüm Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/tr/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/tr/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/tr/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/tr/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.<br/>            Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/tr/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesinden mevcut bir ses nesnesi kullanarak şekil koleksiyonunun sonuna ekler. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak belirtilen indekste şekil koleksiyonuna ekler. |
| [`to_array(self)`](/slides/python-net/tr/aspose.slides/shapecollection/to_array/#) | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [`to_array(self, start_index, count)`](/slides/python-net/tr/aspose.slides/shapecollection/to_array/#int-int) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [`reorder(self, index, shape)`](/slides/python-net/tr/aspose.slides/shapecollection/reorder/#int-ishape) | Belirtilen şekli şekil koleksiyonu içinde yeni bir konuma taşır. |
| [`reorder(self, index, shapes)`](/slides/python-net/tr/aspose.slides/shapecollection/reorder/#int-listishape) | Belirtilen şekilleri şekil koleksiyonu içinde taşıyarak belirtilen indeksten başlayarak yerleştirir. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Varsayılan biçimlendirmeyle yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Yeni bir otomatik şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Yeni bir otomatik şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [`add_group_shape(self)`](/slides/python-net/tr/aspose.slides/shapecollection/add_group_shape/#) | Yeni bir boş grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler.<br/>            Grubun çerçevesi, içine eklenen şekillerin sığması için otomatik olarak ayarlanır. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Varsayılan şablon stilinde yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler,<br/>            isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, varsayılan şablon stilini uygular. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/tr/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.<br/>            Yeni şekil, `source_shape` genişliğini ve yüksekliğini korur. |
| [`add_clone(self, source_shape)`](/slides/python-net/tr/aspose.slides/shapecollection/add_clone/#ishape) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.<br/>            Kopyalanan şekil, orijinalin konumunu ve boyutunu korur. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.<br/>            Yeni şekil, `source_shape` genişliğini ve yüksekliğini korur. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_clone/#int-ishape) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.<br/>            Kopyalanan şekil, orijinalin konumunu ve boyutunu korur. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/tr/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Yeni bir Özet Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Yeni bir Özet Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Yeni bir video çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | CD parçasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | CD parçasına bağlanan yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`index_of(self, shape)`](/slides/python-net/tr/aspose.slides/shapecollection/index_of/#ishape) | Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır tabanlı indeksini döndürür. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/tr/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_group_shape(self, index)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_group_shape/#int) | Yeni bir boş grup şekli oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.<br/>            Grubun çerçevesi, içine eklenen şekillerin sığması için otomatik olarak ayarlanır. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/tr/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/tr/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/tr/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Yeni bir tablo oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/shapecollection/remove_at/#int) | Belirtilen indeksteki şekli şekil koleksiyonundan kaldırır. |
| [`remove(self, shape)`](/slides/python-net/tr/aspose.slides/shapecollection/remove/#ishape) | Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides/shapecollection/clear/#) | Şekil koleksiyonundaki tüm şekilleri kaldırır. |


### Ayrıca Bakınız
* sınıf [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)