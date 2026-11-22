---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ifontsmanager/
---
## IFontsManager sınıf

Sunum genelinde yazı tiplerini yönetir.

IFontsManager türü aşağıdaki üyeleri ortaya çıkar.

## Özellikler

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/tr/aspose.slides/ifontsmanager/font_subst_rule_list/) | Renderleme sırasında kullanılacak yazı tipi ikameleri<br/>            Okuma/yazma [`IFontSubstRuleCollection`](/slides/python-net/tr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/tr/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Kullanıcının, yedekleme işleviyle uygun ikameler sağlamak için yazı tipleri koleksiyonlarını yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder<br/>            Okuma/yazma [`IFontFallBackRulesCollection`](/slides/python-net/tr/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/tr/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Kaydedilmiş yazı tiplerinin, aynı yazı tipi adı ve stiline sahip gömülü yazı tiplerine göre tercih edilip edilmeyeceğini belirler.<br/>            Etkinleştirildiğinde, eşleşen gömülü yazı tipleri dışa aktarım sırasında ilgili kayıtlı yazı tipleriyle geçici olarak değiştirilir. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_substitutions/#) | Sunumun renderlemesi sırasında değiştirilecek yazı tipleri hakkında bilgileri alır. |
| [`get_substitutions(self, slides)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_substitutions/#listint) | Belirtilen slaytların renderlemesi sırasında değiştirilecek yazı tipleri hakkında bilgileri alır. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Yerleşik yazı tipini ekler.<br/>            Herhangi bir yazı tipini kopyalarken çoğu yazı tipinin telif hakkına sahip olduğunu unutmayın. Önceden bir yazı tipinin lisansını bulun<br/>            ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. Font verisi None ise veya bu yazı tipi zaten gömülmüşse ArgumentException istisnası fırlatılabilir |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Yerleşik yazı tipini ekler<br/>            Herhangi bir yazı tipi eklerken çoğu yazı tipinin telif hakkına sahip olduğunu unutmayın. Önceden bir yazı tipinin lisansını bulun<br/>            ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. Font verisi None ise veya bu yazı tipi zaten gömülmüşse ArgumentException istisnası fırlatılabilir |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/tr/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Sunumda yazı tipini değiştir. |
| [`replace_font(self, subst_rule)`](/slides/python-net/tr/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Sunumda [`IFontSubstRule`](/slides/python-net/tr/aspose.slides/ifontsubstrule) içinde verilen bilgileri kullanarak yazı tipini değiştir. |
| [`replace_font(self, subst_rules)`](/slides/python-net/tr/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Sunumda [`IFontSubstRule`](/slides/python-net/tr/aspose.slides/ifontsubstrule) koleksiyonunda verilen bilgileri kullanarak yazı tipini değiştir. |
| [`get_fonts(self)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_fonts/#) | Sunumda kullanılan yazı tiplerini döndürür. |
| [`get_embedded_fonts(self)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Sunumda gömülü olan yazı tiplerini döndürür. |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/tr/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Gömülü yazı tipini kaldırır. |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Belirtilen bir yazı tipi stili ve yazı tipi verisi için font verisini temsil eden bayt dizisini alır. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/tr/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Verilen bayt dizisi ve yazı tipi adından bir fontun gömme seviyesini belirler. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)