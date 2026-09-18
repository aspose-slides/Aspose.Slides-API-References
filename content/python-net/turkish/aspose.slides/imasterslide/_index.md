---
title: IMasterSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/imasterslide/
---
## IMasterSlide sınıf

Bir sunumda ana slaytı temsil eder.

IMasterSlide türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/imasterslide/header_footer_manager/) | Ana slaydın HeaderFooter yöneticisini döndürür.<br/>            Salt okunur [`IMasterSlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/tr/aspose.slides/imasterslide/title_style/) | Başlık metninin stilini döndürür.<br/>            Salt okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/tr/aspose.slides/imasterslide/body_style/) | Gövde metninin stilini döndürür.<br/>            Salt okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/tr/aspose.slides/imasterslide/other_style/) | Diğer metnin stilini döndürür.<br/>            Salt okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/tr/aspose.slides/imasterslide/layout_slides/) | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür.<br/>            Salt okunur [`IMasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/tr/aspose.slides/imasterslide/preserve/) | İlgili ana slaytın, o ana slaytı izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler.<br/>            Not: Aspose.Slides, kullanılmayan bir ana slaytı kendiliğinden asla kaldırmaz, <br/>            kullanılmayan ana slaytları gerçekten kaldırmak için **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Okunur/yazılabilir **bool**. |
| [`has_depending_slides`](/slides/python-net/tr/aspose.slides/imasterslide/has_depending_slides/) | Bu ana slayta bağımlı en az bir slayt varsa **true** döndürür.<br/>            Salt okunur **bool**. |
| [`drawing_guides`](/slides/python-net/tr/aspose.slides/imasterslide/drawing_guides/) | Ana slayt için çizim kılavuzlarının bir koleksiyonunu döndürür.<br/>            Salt okunur [`IDrawingGuidesCollection`](/slides/python-net/tr/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/tr/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/tr/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/tr/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/tr/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/tr/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/tr/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/tr/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/imasterslide/theme_manager/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/tr/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Mevcut ana slaytı temel alarak yeni bir ana slayt oluşturur, ona dış tema uygular <br/>            ve oluşturulan ana slaytı tüm bağımlı slaytlara uygular. |
| [`get_depending_slides(self)`](/slides/python-net/tr/aspose.slides/imasterslide/get_depending_slides/#) | Bu ana slayta bağımlı tüm slaytları içeren bir dizi döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/imasterslide/create_theme_effective/#) |  |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)