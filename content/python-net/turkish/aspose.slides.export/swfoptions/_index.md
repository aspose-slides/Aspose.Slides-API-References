---
title: SwfOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/swfoptions/
---
## SwfOptions sınıfı

Bir sunumun Swf biçiminde nasıl kaydedileceğini kontrol eden seçenekler sağlar.

**Inheritance:**[`SwfOptions`](/slides/python-net/tr/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)

SwfOptions türü aşağıdaki üyeleri ortaya çıkarır:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/swfoptions/__init__/#) | Varsayılan yapıcı. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/swfoptions/warning_callback/) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğini ya da iptal edileceğini belirleyen bir nesneyi döndürür veya ayarlar.<br/>            Read/write [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/swfoptions/progress_callback/) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder.<br/>            Bkz [`IProgressCallback`](/slides/python-net/tr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/swfoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/swfoptions/gradient_style/) | Gradyanın görsel stilini döndürür veya ayarlar.<br/>            Read/write [`GradientStyle`](/slides/python-net/tr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/swfoptions/skip_java_script_links/) | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir.<br/>            Read/write **bool**. Varsayılan **false**. |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir.<br/>            Varsayılan `false`. |
| [`compressed`](/slides/python-net/tr/aspose.slides.export/swfoptions/compressed/) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir.<br/>            Varsayılan `true`. |
| [`viewer_included`](/slides/python-net/tr/aspose.slides.export/swfoptions/viewer_included/) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirtir.<br/>            Varsayılan `true`. |
| [`show_page_border`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_page_border/) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan **true**. |
| [`show_full_screen`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_full_screen/) | Tam ekran düğmesini göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| [`show_page_stepper`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_page_stepper/) | Sayfa adımını göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| [`show_search`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_search/) | Arama bölümünü göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| [`show_top_pane`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_top_pane/) | Tüm üst bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| [`show_bottom_pane`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_bottom_pane/) | Alt bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| [`show_left_pane`](/slides/python-net/tr/aspose.slides.export/swfoptions/show_left_pane/) | Sol bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| [`start_open_left_pane`](/slides/python-net/tr/aspose.slides.export/swfoptions/start_open_left_pane/) | Sol bölme açık olarak başlat. flashvars içinde geçersiz kılınabilir. Varsayılan **false**. |
| [`enable_context_menu`](/slides/python-net/tr/aspose.slides.export/swfoptions/enable_context_menu/) | Bağlam menüsünü etkinleştir/devre dışı bırak. Varsayılan **true**. |
| [`logo_image_bytes`](/slides/python-net/tr/aspose.slides.export/swfoptions/logo_image_bytes/) | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü.<br/>            Görüntü 32x64 piksel PNG olmalı, aksi takdirde logo düzgün gösterilemez. |
| [`logo_link`](/slides/python-net/tr/aspose.slides.export/swfoptions/logo_link/) | Logonun tam köprü adresini alır veya ayarlar.<br/>            Yalnızca bir [`SwfOptions.logo_image_bytes`](/slides/python-net/tr/aspose.slides.export/swfoptions/logo_image_bytes) belirtilmişse etkili olur. |
| [`jpeg_quality`](/slides/python-net/tr/aspose.slides.export/swfoptions/jpeg_quality/) | JPEG görüntü kalitesini belirtir.<br/>            Varsayılan 95. |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/swfoptions/slides_layout_options/) | Sunumu [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions) dışa aktarırken slaytların sayfa üzerine yerleştirileceği modu alır veya ayarlar.<br/>            Bu özellik [`HandoutLayoutingOptions`](/slides/python-net/tr/aspose.slides.export/handoutlayoutingoptions) türündeki nesnelerin atanmasını desteklemez. |

### Ayrıca Bakınız
* sınıf [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)
* sınıf [`SwfOptions`](/slides/python-net/tr/aspose.slides.export/swfoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)