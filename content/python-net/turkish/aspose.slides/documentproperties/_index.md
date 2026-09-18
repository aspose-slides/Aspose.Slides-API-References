---
title: DocumentProperties class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/documentproperties/
---
## DocumentProperties sınıf

Bir sunumun özelliklerini temsil eder.

DocumentProperties türü aşağıdaki üyeleri ortaya çıkarır:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides/documentproperties/__init__/#) | [`DocumentProperties`](/slides/python-net/tr/aspose.slides/documentproperties) sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`app_version`](/slides/python-net/tr/aspose.slides/documentproperties/app_version/) | Uygulama sürümünü döndürür.<br/>            Salt okunur **str**. |
| [`name_of_application`](/slides/python-net/tr/aspose.slides/documentproperties/name_of_application/) | Uygulamanın adını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`company`](/slides/python-net/tr/aspose.slides/documentproperties/company/) | Şirket özelliğini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`manager`](/slides/python-net/tr/aspose.slides/documentproperties/manager/) | Yönetici özelliğini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`presentation_format`](/slides/python-net/tr/aspose.slides/documentproperties/presentation_format/) | Sunumun hedef formatını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`shared_doc`](/slides/python-net/tr/aspose.slides/documentproperties/shared_doc/) | Sunumun birden fazla kişi arasında paylaşılıp paylaşılamadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`application_template`](/slides/python-net/tr/aspose.slides/documentproperties/application_template/) | Uygulamanın şablonunu döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`total_editing_time`](/slides/python-net/tr/aspose.slides/documentproperties/total_editing_time/) | Sunumun toplam düzenleme süresi.<br/>            Okunur/Yazılabilir **System.TimeSpan**. |
| [`title`](/slides/python-net/tr/aspose.slides/documentproperties/title/) | Sunumun başlığını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`subject`](/slides/python-net/tr/aspose.slides/documentproperties/subject/) | Sunumun konusunu döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`author`](/slides/python-net/tr/aspose.slides/documentproperties/author/) | Sunumun yazarını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`keywords`](/slides/python-net/tr/aspose.slides/documentproperties/keywords/) | Sunumun anahtar kelimelerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`comments`](/slides/python-net/tr/aspose.slides/documentproperties/comments/) | Sunumun yorumlarını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`category`](/slides/python-net/tr/aspose.slides/documentproperties/category/) | Sunumun kategorisini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`created_time`](/slides/python-net/tr/aspose.slides/documentproperties/created_time/) | Sunumun oluşturulma tarihini döndürür.<br/>            Değerler UTC olarak verilir.<br/>            Okunur/Yazılabilir **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/tr/aspose.slides/documentproperties/last_saved_time/) | Sunumun en son değiştirilme tarihini döndürür.<br/>            Değerler UTC olarak verilir.<br/>            Presentation.DocumentProperties için salt okunur (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). <br/>            [`IPresentationInfo.read_document_properties`](/slides/python-net/tr/aspose.slides/ipresentationinfo/read_document_properties) yöntemiyle dönen DocumentProperties örneği üzerinden değiştirilebilir.<br/>            Lütfen **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** yöntem özetindeki örneği inceleyin. |
| [`last_printed`](/slides/python-net/tr/aspose.slides/documentproperties/last_printed/) | Sunumun en son yazdırıldığı tarihi döndürür.<br/>            Okunur/Yazılabilir **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/tr/aspose.slides/documentproperties/last_saved_by/) | Sunumu en son değiştiren kişinin adını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`revision_number`](/slides/python-net/tr/aspose.slides/documentproperties/revision_number/) | Sunum revizyon numarasını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **int**. |
| [`content_status`](/slides/python-net/tr/aspose.slides/documentproperties/content_status/) | Sunumun içerik durumunu döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`content_type`](/slides/python-net/tr/aspose.slides/documentproperties/content_type/) | Sunumun içerik türünü döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`hyperlink_base`](/slides/python-net/tr/aspose.slides/documentproperties/hyperlink_base/) | HyperlinkBase belge özelliğini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`count_of_custom_properties`](/slides/python-net/tr/aspose.slides/documentproperties/count_of_custom_properties/) | Bir koleksiyonda bulunan özel özelliklerin gerçek sayısını döndürür.<br/>            Salt okunur **int**. |
| [`scale_crop`](/slides/python-net/tr/aspose.slides/documentproperties/scale_crop/) | Belge küçük resminin görüntüleme modunu gösterir. <br/>            Görüntüleme için belge küçük resminin ölçeklendirilmesini etkinleştirmek için bu öğeyi **true** olarak ayarlayın. <br/>            Görüntüleme alanına sadece sığan bölümleri göstermek için kırpılmasını etkinleştirmek amacıyla bu öğeyi **false** olarak ayarlayın.<br/>            Okunur/Yazılabilir **bool**. |
| [`links_up_to_date`](/slides/python-net/tr/aspose.slides/documentproperties/links_up_to_date/) | Belgedeki bağlantıların güncel olup olmadığını gösterir. <br/>            Bağlantıların güncellendiğini belirtmek için bu öğeyi **true** olarak ayarlayın. <br/>            Bağlantıların artık geçerli olmadığını belirtmek için bu öğeyi **false** olarak ayarlayın.<br/>            Okunur/Yazılabilir **bool**. |
| [`hyperlinks_changed`](/slides/python-net/tr/aspose.slides/documentproperties/hyperlinks_changed/) | Bu bölümdeki bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. <br/>            Bu belgeyi açacak bir sonraki üretici, bu bölümde belirtilen yeni bağlantılarla bağlantı ilişkilerini güncelleyecektir.<br/>            Okunur/Yazılabilir **bool**. |
| [`slides`](/slides/python-net/tr/aspose.slides/documentproperties/slides/) | Sunum belgesindeki toplam slayt sayısını döndürür.<br/tr/>            Salt okunur **int**. |
| [`hidden_slides`](/slides/python-net/tr/aspose.slides/documentproperties/hidden_slides/) | Sunum belgesindeki gizli slayt sayısını döndürür.<br/>            Salt okunur **int**. |
| [`notes`](/slides/python-net/tr/aspose.slides/documentproperties/notes/) | Not içeren slaytların sayısını döndürür.<br/>            Salt okunur **int**. |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/documentproperties/paragraphs/) | Belgede bulunan paragraf sayısını döndürür (uygunsa).<br/>            Salt okunur **int**. |
| [`words`](/slides/python-net/tr/aspose.slides/documentproperties/words/) | Belgede bulunan kelime sayısını döndürür.<br/>            Salt okunur **int**. |
| [`multimedia_clips`](/slides/python-net/tr/aspose.slides/documentproperties/multimedia_clips/) | Belgede bulunan ses veya video klip sayısını döndürür.<br/>            Salt okunur **int**. |
| [`titles_of_parts`](/slides/python-net/tr/aspose.slides/documentproperties/titles_of_parts/) | Her belge bölümünün başlığını belirtir. <br/>            Bu bölümler gerçek belge bölümleri değil, belge bölümlerinin kavramsal temsilidir.<br/>            Salt okunur **List[str]**. |
| [`heading_pairs`](/slides/python-net/tr/aspose.slides/documentproperties/heading_pairs/) | Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir.<br/>            Salt okunur **List[IHeadingPair]**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir bool değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir int değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir DateTime değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir string değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Adlandırılmış bir bool özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Adlandırılmış bir int özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Adlandırılmış bir string özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Adlandırılmış bir float özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Adlandırılmış bir double özel özelliği ayarlar. |
| [`get_custom_property_name(self, index)`](/slides/python-net/tr/aspose.slides/documentproperties/get_custom_property_name/#int) | Belirtilen indeksteki özel özellik adını döndürür. |
| [`remove_custom_property(self, name)`](/slides/python-net/tr/aspose.slides/documentproperties/remove_custom_property/#str) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [`contains_custom_property(self, name)`](/slides/python-net/tr/aspose.slides/documentproperties/contains_custom_property/#str) | Belirtilen adla bir özel özelliğin varlığını kontrol eder. |
| [`clear_custom_properties(self)`](/slides/python-net/tr/aspose.slides/documentproperties/clear_custom_properties/#) | Tüm özel özellikleri kaldırır. |
| [`get_sensitivity_labels(self)`](/slides/python-net/tr/aspose.slides/documentproperties/get_sensitivity_labels/#) | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerini bir dizi olarak alır. |
| [`clear_built_in_properties(self)`](/slides/python-net/tr/aspose.slides/documentproperties/clear_built_in_properties/#) | Tüm yerleşik özellikleri varsayılan değerlere temizler ve ayarlar. |
| [`clone(self)`](/slides/python-net/tr/aspose.slides/documentproperties/clone/#) | Mevcut nesneyi klonlar |
| [`clone_t(self)`](/slides/python-net/tr/aspose.slides/documentproperties/clone_t/#) | Mevcut nesneyi klonlar |

### Ayrıca Bakınız
* sınıf [`DocumentProperties`](/slides/python-net/tr/aspose.slides/documentproperties)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)