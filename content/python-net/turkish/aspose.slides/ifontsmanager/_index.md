---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ifontsmanager/
---
## IFontsManager sınıfı

Sunum boyunca yazı tiplerini yönetir.

IFontsManager türü aşağıdaki üyelere sahiptir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/tr/aspose.slides/ifontsmanager/font_subst_rule_list/) | Render sırasında kullanılacak yazı tipi ikameleri<br/>            Okuma/Yazma [`IFontSubstRuleCollection`](/slides/python-net/tr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/tr/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; bu kurallar, yazı tiplerinin doğru ikameleri için yedekleme işleviyle koleksiyonların yönetilmesini sağlar<br/>            Okuma/Yazma [`IFontFallBackRulesCollection`](/slides/python-net/tr/aspose.slides/ifontfallbackrulescollection). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_substitutions/#) | Sunumun render işlemi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [`get_substitutions(self, slides)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_substitutions/#listint) | Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Gömülü yazı tipini ekler.<br/>            Çoğu yazı tipinin telif hakkına sahip olduğunu aklınızda bulundurun. Önce bir yazı tipinin lisansını bulun<br/>            ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. Font verisi None ise veya bu yazı tipi zaten gömülü ise ArgumentException fırlatılabilir |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Gömülü yazı tipini ekler.<br/>            Çoğu yazı tipinin telif hakkına sahip olduğunu aklınızda bulundurun. Önce bir yazı tipinin lisansını bulun<br/>            ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. Font verisi None ise veya bu yazı tipi zaten gömülü ise ArgumentException fırlatılabilir |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/tr/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Sunumda yazı tipini değiştir |
| [`replace_font(self, subst_rule)`](/slides/python-net/tr/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | [`IFontSubstRule`](/slides/python-net/tr/aspose.slides/ifontsubstrule) içinde verilen bilgiler kullanılarak sunumda yazı tipini değiştir |
| [`replace_font(self, subst_rules)`](/slides/python-net/tr/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | [`IFontSubstRule`](/slides/python-net/tr/aspose.slides/ifontsubstrule) koleksiyonunda verilen bilgiler kullanılarak sunumda yazı tipini değiştir |
| [`get_fonts(self)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_fonts/#) | Sunumda kullanılan yazı tiplerini döndürür |
| [`get_embedded_fonts(self)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Sunumda gömülü olan yazı tiplerini döndürür |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/tr/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Gömülü yazı tipini kaldırır |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Belirtilen bir yazı tipi stili ve yazı tipi verisi için font verisini temsil eden bayt dizisini alır. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Verilen bayt dizisi ve font adı üzerinden bir fontun gömme seviyesini belirler. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)