---
title: ILoadOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iloadoptions/
---
## ILoadOptions sınıf

Bir sunumu yüklerken ek seçenekleri (örneğin biçim veya varsayılan yazı tipi) belirtmeye olanak tanır.

ILoadOptions türü aşağıdaki üyeleri içerir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`load_format`](/slides/python-net/tr/aspose.slides/iloadoptions/load_format/) | Yüklenecek bir sunumun biçimini döndürür veya ayarlar.<br/>            Read/write [`LoadFormat`](/slides/python-net/tr/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides/iloadoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini döndürür veya ayarlar.<br/>            Read-write **str**. |
| [`default_symbol_font`](/slides/python-net/tr/aspose.slides/iloadoptions/default_symbol_font/) | Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini döndürür veya ayarlar.<br/>            Read-write **str**. |
| [`default_asian_font`](/slides/python-net/tr/aspose.slides/iloadoptions/default_asian_font/) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini döndürür veya ayarlar.<br/>            Read-write **str**. |
| [`password`](/slides/python-net/tr/aspose.slides/iloadoptions/password/) | Parolayı alır veya ayarlar.<br/>            Read-write **str**. |
| [`only_load_document_properties`](/slides/python-net/tr/aspose.slides/iloadoptions/only_load_document_properties/) | Bu özellik, sunum dosyası parola ile korumalıysa anlamlıdır.<br/>            true değeri, yalnızca belge özelliklerinin şifreli bir sunum dosyasından yüklenmesi gerektiği ve parolanın göz ardı edilmesi anlamına gelir.<br/>            false değeri, tüm şifreli sunumun doğru parola kullanılarak yüklenmesi gerektiği anlamına gelir.<br/>            Sunum şifreli değilse özellik değeri her zaman göz ardı edilir.<br/>            Şifreli bir dosyanın belge özellikleri halka açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna fırlatılır.<br/>            Read-write **bool**. |
| [`warning_callback`](/slides/python-net/tr/aspose.slides/iloadoptions/warning_callback/) | Uyarıları alan ve yükleme <br/>            sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar.<br/>            Read/write [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/tr/aspose.slides/iloadoptions/blob_management_options/) | Binary Large Objects (BLOBs) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder,<br/>            örneğin geçici dosyaların kullanılması veya bellek içindeki maksimum BLOB baytları. Bu seçenekler, belirli bir ortam ya da gereksinim için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.<br/>            Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir - yani BLOB bir ses, video ya da sunum kendisi olabilir. |
| [`document_level_font_sources`](/slides/python-net/tr/aspose.slides/iloadoptions/document_level_font_sources/) | Sunum tarafından kullanılacak harici yazı tiplerinin kaynaklarını belirtir.<br/>            Bu yazı tipleri, sunumun tüm ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz. |
| [`interruption_token`](/slides/python-net/tr/aspose.slides/iloadoptions/interruption_token/) | Kesinti isteklerini izlemek için kullanılan belirteç.<br/>            <br/>            Bu belirteç, tüm [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örnek ömrünü yönetir. Sunum <br/>            yükleme veya kaydetme gibi uzun süren bir işlem, [`IInterruptionTokenSource.interrupt`](/slides/python-net/tr/aspose.slides/iinterruptiontokensource/interrupt) yöntemi çağrılarak [`IInterruptionTokenSource`](/slides/python-net/tr/aspose.slides/iinterruptiontokensource) üzerinden kesintiye uğratılacaktır. |
| [`resource_loading_callback`](/slides/python-net/tr/aspose.slides/iloadoptions/resource_loading_callback/) | Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü döndürür veya ayarlar.<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/tr/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/tr/aspose.slides/iloadoptions/spreadsheet_options/) | Ek elektronik tablo davranışlarını belirtmek için kullanılabilecek seçenekleri temsil eder. |
| [`default_text_language`](/slides/python-net/tr/aspose.slides/iloadoptions/default_text_language/) | Sunum metni için varsayılan dili döndürür veya ayarlar.<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/tr/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Sunum yüklenirken Aspose.Slides'in tüm gömülü ikili nesneleri silip silmeyeceğini belirler.<br/>            <br/>Gömülü ikili nesnelerin türleri:<br/><br/><br/>* VBA Projesi [`IPresentation.vba_project`](/slides/python-net/tr/aspose.slides/ipresentation/vba_project)<br/>* OLE Nesnesi gömülü veri [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Kontrol ikili veri [`IControl.active_x_control_binary`](/slides/python-net/tr/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)