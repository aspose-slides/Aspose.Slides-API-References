---
title: IDocumentProperties class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/idocumentproperties/
---
## IDocumentProperties sınıfı

Bir sunumun özelliklerini temsil eder.

IDocumentProperties türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`app_version`](/slides/python-net/tr/aspose.slides/idocumentproperties/app_version/) | Uygulama sürümünü döndürür.<br/>            Yalnızca okuma **str**. |
| [`name_of_application`](/slides/python-net/tr/aspose.slides/idocumentproperties/name_of_application/) | Uygulamanın adını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`company`](/slides/python-net/tr/aspose.slides/idocumentproperties/company/) | Şirket özelliğini döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`manager`](/slides/python-net/tr/aspose.slides/idocumentproperties/manager/) | Yönetici özelliğini döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`presentation_format`](/slides/python-net/tr/aspose.slides/idocumentproperties/presentation_format/) | Bir sunumun hedef formatını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`shared_doc`](/slides/python-net/tr/aspose.slides/idocumentproperties/shared_doc/) | Sunumun birden çok kişi arasında paylaşılıp paylaşılmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`application_template`](/slides/python-net/tr/aspose.slides/idocumentproperties/application_template/) | Bir uygulamanın şablonunu döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`total_editing_time`](/slides/python-net/tr/aspose.slides/idocumentproperties/total_editing_time/) | Bir sunumun toplam düzenleme süresi.<br/>            Okuma/yazma **System.TimeSpan**. |
| [`title`](/slides/python-net/tr/aspose.slides/idocumentproperties/title/) | Bir sunumun başlığını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`subject`](/slides/python-net/tr/aspose.slides/idocumentproperties/subject/) | Bir sunumun konusunu döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`author`](/slides/python-net/tr/aspose.slides/idocumentproperties/author/) | Bir sunumun yazarını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`keywords`](/slides/python-net/tr/aspose.slides/idocumentproperties/keywords/) | Bir sunumun anahtar kelimelerini döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`comments`](/slides/python-net/tr/aspose.slides/idocumentproperties/comments/) | Bir sunumun yorumlarını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`category`](/slides/python-net/tr/aspose.slides/idocumentproperties/category/) | Bir sunumun kategorisini döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`created_time`](/slides/python-net/tr/aspose.slides/idocumentproperties/created_time/) | Bir sunumun oluşturulma tarihini döndürür.<br/>            Değerler UTC'dedir.<br/>            Okuma/yazma **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/tr/aspose.slides/idocumentproperties/last_saved_time/) | Bir sunumun son değiştirilme tarihini döndürür.<br/>            Değerler UTC'dedir.<br/>            Presentation.DocumentProperties durumunda yalnızca okuma (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). <br/>            [`IPresentationInfo.read_document_properties`](/slides/python-net/tr/aspose.slides/ipresentationinfo/read_document_properties) yöntemi tarafından döndürülen DocumentProperties örneği aracılığıyla değiştirilebilir.<br/>            Lütfen **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** yöntem özetinde örneğe bakın. |
| [`last_printed`](/slides/python-net/tr/aspose.slides/idocumentproperties/last_printed/) | Bir sunumun en son ne zaman basıldığını döndürür.<br/>            Okuma/yazma **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/tr/aspose.slides/idocumentproperties/last_saved_by/) | Sunumu en son değiştiren kişinin adını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`revision_number`](/slides/python-net/tr/aspose.slides/idocumentproperties/revision_number/) | Sunum revizyon numarasını döndürür veya ayarlar.<br/>            Okuma/yazma **int**. |
| [`content_status`](/slides/python-net/tr/aspose.slides/idocumentproperties/content_status/) | Sunumun içerik durumunu döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`content_type`](/slides/python-net/tr/aspose.slides/idocumentproperties/content_type/) | Sunumun içerik türünü döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`hyperlink_base`](/slides/python-net/tr/aspose.slides/idocumentproperties/hyperlink_base/) | HyperlinkBase belge özelliğini döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`scale_crop`](/slides/python-net/tr/aspose.slides/idocumentproperties/scale_crop/) | Belge küçük resminin görüntüleme modunu belirtir. <br/>            Bu öğeyi **true** olarak ayarlayın; belge küçük resminin ekrana ölçeklenmesini etkinleştirir. <br/>            Bu öğeyi **false** olarak ayarlayın; belge küçük resminin yalnızca ekrana sığan bölümleri gösterecek şekilde kırpılmasını etkinleştirir.<br/>            Okuma/yazma **bool**. |
| [`links_up_to_date`](/slides/python-net/tr/aspose.slides/idocumentproperties/links_up_to_date/) | Belgedeki hiperlinklerin güncel olup olmadığını belirtir. <br/>            Bu öğeyi **true** olarak ayarlayın; hiperlinklerin güncellendiğini gösterir. <br/>            Bu öğeyi **false** olarak ayarlayın; hiperlinklerin güncel olmadığını gösterir.<br/>            Okuma/yazma **bool**. |
| [`hyperlinks_changed`](/slides/python-net/tr/aspose.slides/idocumentproperties/hyperlinks_changed/) | Bu bölümde bir veya daha fazla hiperlinkin üretici tarafından yalnızca bu bölümde güncellendiğini belirtir. <br/>            Bu belgeyi bir sonraki üretici açtığında, bu bölümde belirtilen yeni hiperlinklerle hiperlink ilişkileri güncellenecektir.<br/>            Okuma/yazma **bool**. |
| [`slides`](/slides/python-net/tr/aspose.slides/idocumentproperties/slides/) | Bir sunum belgesindeki toplam slayt sayısını belirtir.<br/tr/>            Yalnızca okuma **int**. |
| [`hidden_slides`](/slides/python-net/tr/aspose.slides/idocumentproperties/hidden_slides/) | Bir sunum belgesindeki gizli slayt sayısını belirtir.<br/>            Yalnızca okuma **int**. |
| [`notes`](/slides/python-net/tr/aspose.slides/idocumentproperties/notes/) | Not içeren bir sunumdaki slayt sayısını belirtir.<br/>            Yalnızca okuma **int**. |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/idocumentproperties/paragraphs/) | Belgede bulunan toplam paragraf sayısını (uygulanabilirse) belirtir.<br/>            Yalnızca okuma **int**. |
| [`words`](/slides/python-net/tr/aspose.slides/idocumentproperties/words/) | Belgedeki toplam kelime sayısını belirtir.<br/>            Yalnızca okuma **int**. |
| [`multimedia_clips`](/slides/python-net/tr/aspose.slides/idocumentproperties/multimedia_clips/) | Belgede bulunan ses veya video kliplerinin toplam sayısını belirtir.<br/>            Yalnızca okuma **int**. |
| [`titles_of_parts`](/slides/python-net/tr/aspose.slides/idocumentproperties/titles_of_parts/) | Her belge kısmının başlığını belirtir. <br/>            Bu kısımlar belge bölümleri değildir; belge bölümlerinin kavramsal temsilleridir.<br/>            Yalnızca okuma **List[str]**. |
| [`heading_pairs`](/slides/python-net/tr/aspose.slides/idocumentproperties/heading_pairs/) | Belge parçalarının gruplandırılmasını ve her gruptaki parça sayısını gösterir.<br/>            Yalnızca okuma **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/tr/aspose.slides/idocumentproperties/count_of_custom_properties/) | Bir koleksiyonda gerçekte bulunan özel özellik sayısını döndürür.<br/>            Yalnızca okuma **int**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir boolean değer alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir tamsayı değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir DateTime değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Özel özelliklerden adlandırılmış bir dize değeri alır. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Adlandırılmış bir boolean özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Adlandırılmış bir tamsayı özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Adlandırılmış bir dize özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Adlandırılmış bir float özel özelliği ayarlar. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/tr/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Adlandırılmış bir double özel özelliği ayarlar. |
| [`get_custom_property_name(self, index)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Belirtilen indeksdeki bir özel özellik adını döndürür. |
| [`remove_custom_property(self, name)`](/slides/python-net/tr/aspose.slides/idocumentproperties/remove_custom_property/#str) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [`contains_custom_property(self, name)`](/slides/python-net/tr/aspose.slides/idocumentproperties/contains_custom_property/#str) | Belirtilen ada sahip bir özel özelliğin varlığını kontrol eder. |
| [`clear_custom_properties(self)`](/slides/python-net/tr/aspose.slides/idocumentproperties/clear_custom_properties/#) | Tüm özel özellikleri kaldırır. |
| [`clear_built_in_properties(self)`](/slides/python-net/tr/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Tüm yerleşik özellikleri temizler ve varsayılan değerleri ayarlar. |
| [`get_sensitivity_labels(self)`](/slides/python-net/tr/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Özel belge özelliklerinden (Microsoft Information Protection SDK Metaverileri) duyarlılık etiketlerinin bir dizisini alır. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)