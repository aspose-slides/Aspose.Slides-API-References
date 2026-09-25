---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islide/
---
## ISlide sınıfı

Represents a slide in a presentation.

The ISlide type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/islide/header_footer_manager/) | Slaytın HeaderFooter yöneticisini döndürür.<br/>            Salt okunur [`ISlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/tr/aspose.slides/islide/slide_number/) | Slayt numarasını döndürür.<br/>            [`IPresentation.slides`](/slides/python-net/tr/aspose.slides/ipresentation/slides) koleksiyonundaki slaytın indeksi her zaman SlideNumber - 1&#x20;e eşittir.<br/>            Okuma/Yazma **int**. |
| [`hidden`](/slides/python-net/tr/aspose.slides/islide/hidden/) | Belirtilen slaydın slayt gösterisi sırasında gizlenip gizlenmediğini belirler.<br/>            Okuma/Yazma **bool**. |
| [`layout_slide`](/slides/python-net/tr/aspose.slides/islide/layout_slide/) | Geçerli slayt için düzen slaydını döndürür veya ayarlar.<br/>            Okuma/Yazma [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/tr/aspose.slides/islide/notes_slide_manager/) | Not slaydına erişim, ekleme ve kaldırma izni verir.<br/>            Salt okunur [`INotesSlideManager`](/slides/python-net/tr/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/tr/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/tr/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/tr/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/tr/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/tr/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/tr/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/tr/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/islide/theme_manager/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/islide/get_image/#float-float) | Özel ölçekleme ile bir görüntü nesnesi döndürür. |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/islide/get_image/#) | Gerçek boyutun %20&#x20;sı kadar bir Küçük Resim nesnesi döndürür. |
| [`get_image(self, image_size)`](/slides/python-net/tr/aspose.slides/islide/get_image/#asposeslidessize) | Belirtilen boyutta bir görüntü nesnesi döndürür. |
| [`get_image(self, options)`](/slides/python-net/tr/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Belirtilen parametrelerle bir Küçük Resim tiff bitmap nesnesi döndürür. |
| [`get_image(self, options)`](/slides/python-net/tr/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Küçük Resim Bitmap nesnesi döndürür. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Özel ölçekleme ile bir Küçük Resim Bitmap nesnesi döndürür. |
| [`get_image(self, options, image_size)`](/slides/python-net/tr/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Belirtilen boyutta bir Küçük Resim Bitmap nesnesi döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/islide/write_as_svg/#iorawiobase) | Slayt içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slayt içeriğini SVG dosyası olarak kaydeder. |
| [`get_slide_comments(self, author)`](/slides/python-net/tr/aspose.slides/islide/get_slide_comments/#icommentauthor) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| [`write_as_emf(self, stream)`](/slides/python-net/tr/aspose.slides/islide/write_as_emf/#iorawiobase) | Slayt içeriğini EMF dosyası olarak kaydeder. |
| [`remove(self)`](/slides/python-net/tr/aspose.slides/islide/remove/#) | Slaytı sunumdan kaldırır. |
| [`reset(self)`](/slides/python-net/tr/aspose.slides/islide/reset/#) | LayoutSlide üzerinde bir prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/islide/create_theme_effective/#) |  |

### Diğer Bilgiler
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)