---
title: LoadOptions class
second_title: Aspose.Slides için Python .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/loadoptions/
---
## LoadOptions sınıfı

Bir sunum yüklenirken ek seçenekleri (örneğin biçim veya varsayılan yazı tipi) belirtmenizi sağlar.

LoadOptions tipi aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides/loadoptions/__init__/#) | Yeni varsayılan yükleme seçenekleri oluşturur. |
| [`__init__(self, load_format)`](/slides/python-net/tr/aspose.slides/loadoptions/__init__/#loadformat) | Yeni yükleme seçenekleri oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`load_format`](/slides/python-net/tr/aspose.slides/loadoptions/load_format/) | Yüklenmekte olan bir sunumun biçimini döndürür veya ayarlar.<br/>            Okuma/Yazma [`LoadFormat`](/slides/python-net/tr/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides/loadoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini döndürür veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`default_symbol_font`](/slides/python-net/tr/aspose.slides/loadoptions/default_symbol_font/) | Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini döndürür veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`default_asian_font`](/slides/python-net/tr/aspose.slides/loadoptions/default_asian_font/) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini döndürür veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`password`](/slides/python-net/tr/aspose.slides/loadoptions/password/) | Parolayı alır veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`only_load_document_properties`](/slides/python-net/tr/aspose.slides/loadoptions/only_load_document_properties/) | Bu özellik, sunum dosyası parola ile korunuyorsa anlamlıdır.<br/>            true değeri, yalnızca belge özelliklerinin şifreli bir sunum dosyasından yüklenmesi gerektiği ve parolanın yok sayılması anlamına gelir.<br/>            false değeri, tüm şifreli sunumun doğru parola kullanılarak yüklenmesi gerektiği anlamına gelir.<br/>            Sunum şifreli değilse, özellik değeri her zaman yok sayılır.<br/>            Şifreli bir dosyanın belge özellikleri halka açık değilse ve özellik değeri true ise, belge özellikleri yüklenemez ve bir istisna fırlatılır.<br/>            Okuma/Yazma **bool**. |
| [`warning_callback`](/slides/python-net/tr/aspose.slides/loadoptions/warning_callback/) | Uyarıları alıp yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar.<br/>            Okuma/Yazma [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/tr/aspose.slides/loadoptions/blob_management_options/) | Binary Large Object'leri (BLOBs) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder,<br/>            örn. geçici dosyaların kullanılması veya bellek içinde maksimum BLOB baytı. Bu seçenekler, belirli bir ortam ya da gereksinim için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.<br/>            Binary Large Object (BLOB), tek bir varlık olarak saklanan ikili veridir - yani BLOB<br/>            ses, video ya da kendisi bir sunum olabilir. |
| [`document_level_font_sources`](/slides/python-net/tr/aspose.slides/loadoptions/document_level_font_sources/) | Sunumun kullanacağı harici yazı tipleri için kaynakları belirtir.<br/>            Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz. |
| [`interruption_token`](/slides/python-net/tr/aspose.slides/loadoptions/interruption_token/) | Kesinti isteklerini izlemek için kullanılan token.<br/>            <br/>            Bu token, tüm [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örneğinin ömrünü yönetir. Yükleme ya da sunumu kaydetme gibi uzun süren bir işlem, [`InterruptionTokenSource.interrupt`](/slides/python-net/tr/aspose.slides/interruptiontokensource/interrupt) metodunun [`InterruptionTokenSource`](/slides/python-net/tr/aspose.slides/interruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılacaktır. |
| [`resource_loading_callback`](/slides/python-net/tr/aspose.slides/loadoptions/resource_loading_callback/) | Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü döndürür veya ayarlar.<br/>            Okuma/Yazma [`IResourceLoadingCallback`](/slides/python-net/tr/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/tr/aspose.slides/loadoptions/spreadsheet_options/) | Elektronik tablolar için seçenekleri alır. Örneğin, bu seçenekler grafikler için formüllerin hesaplanmasını etkiler. |
| [`default_text_language`](/slides/python-net/tr/aspose.slides/loadoptions/default_text_language/) | Sunum metni için varsayılan dili döndürür veya ayarlar.<br/>             Okuma/Yazma **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/tr/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Sunum yüklenirken Aspose.Slides'in tüm gömülü ikili nesneleri silip silmeyeceğini belirler.<br/>            <br/>Gömülü ikili nesnelerin türleri:<br/><br/><br/>* VBA Projesi [`IPresentation.vba_project`](/slides/python-net/tr/aspose.slides/ipresentation/vba_project)<br/>* OLE Nesnesi gömülü veri [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Denetimi ikili veri [`IControl.active_x_control_binary`](/slides/python-net/tr/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Okuma/Yazma **bool**. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)