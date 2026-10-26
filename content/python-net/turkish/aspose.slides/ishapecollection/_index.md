---
title: IShapeCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/
---
## IShapeCollection class

Şekillerin bir koleksiyonunu temsil eder.

IShapeCollection türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Property | Açıklama |
| :- | :- |
| [`parent_group`](/slides/python-net/tr/aspose.slides/ishapecollection/parent_group/) | Şekil koleksiyonu için üst grup şekil nesnesini alır.<br/>Yalnızca okunabilir [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |

Belirtilen dizindeki öğeyi alır. Yalnızca okunabilir [`IShape`](/slides/python-net/tr/aspose.slides/ishape).

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/ishapecollection/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Önceden tanımlı bir görüntü ile yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Gömülü bir WAV dosyası içeren yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Mevcut bir ses nesnesini Presentation.Audios listesinden kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Gömülü bir WAV dosyası içeren yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Mevcut bir ses nesnesini Presentation.Audios listesinden kullanarak yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`to_array(self)`](/slides/python-net/tr/aspose.slides/ishapecollection/to_array/#) | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [`to_array(self, start_index, count)`](/slides/python-net/tr/aspose.slides/ishapecollection/to_array/#int-int) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [`reorder(self, index, shape)`](/slides/python-net/tr/aspose.slides/ishapecollection/reorder/#int-ishape) | Belirtilen şekli şekil koleksiyonu içinde yeni bir konuma taşır. |
| [`reorder(self, index, shapes)`](/slides/python-net/tr/aspose.slides/ishapecollection/reorder/#int-listishape) | Belirtilen şekilleri şekil koleksiyonu içinde hareket ettirir, verilen dizinden itibaren yerleştirir. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Varsayılan biçimlendirmeye sahip yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Yeni bir otomatik şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Yeni bir otomatik şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini başlatır. |
| [`add_group_shape(self)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_group_shape/#) | Boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grup çerçevesi, eklenen şekillere göre otomatik olarak ayarlanır. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Varsayılan şablon stiline sahip yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler, varsayılan şablon stilini uygular. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil `source_shape` nesnesinin genişliğini ve yüksekliğini korur. |
| [`add_clone(self, source_shape)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_clone/#ishape) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Kopyalanan şekil orijinalin konum ve boyutunu korur. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Yeni şekil `source_shape` nesnesinin genişliğini ve yüksekliğini korur. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Kopyalanan şekil orijinalin konum ve boyutunu korur. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Yeni bir video çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | CD parçasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | CD parçasına bağlanan yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`index_of(self, shape)`](/slides/python-net/tr/aspose.slides/ishapecollection/index_of/#ishape) | Koleksiyonda belirtilen şeklin ilk oluşumunun sıfır tabanlı dizinini döndürür. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_group_shape(self, index)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_group_shape/#int) | Boş bir grup şekli oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Grup çerçevesi, eklenen şekillere göre otomatik olarak ayarlanır. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/tr/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/tr/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Yeni bir tablo oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/ishapecollection/remove_at/#int) | Belirtilen dizindeki şekli şekil koleksiyonundan kaldırır. |
| [`remove(self, shape)`](/slides/python-net/tr/aspose.slides/ishapecollection/remove/#ishape) | Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides/ishapecollection/clear/#) | Şekil koleksiyonundaki tüm şekilleri kaldırır. |

### Ayrıca Bakınız
* sınıf [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)