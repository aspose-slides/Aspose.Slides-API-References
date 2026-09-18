---
title: FontsManager class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/fontsmanager/
---
## FontsManager sınıf

Sunum boyunca fontları yönetir.

FontsManager türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/tr/aspose.slides/fontsmanager/font_subst_rule_list/) | Render sırasında kullanılacak font ikameleri.<br/>            Okuma/yazma [`IFontSubstRuleCollection`](/slides/python-net/tr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/tr/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Kullanıcının, fontların uygun ikameleri için geri dönüş (fallback) işlevselliğiyle yönetilmesi amacıyla FontFallBack kurallarının bir koleksiyonunu temsil eder<br/>            Okuma/yazma [`IFontFallBackRulesCollection`](/slides/python-net/tr/aspose.slides/ifontfallbackrulescollection). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_substitutions/#) | Sunumun render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır. |
| [`get_substitutions(self, slides)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_substitutions/#listint) | Belirtilen slaytların render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Embedded font ekler<br/>            Herhangi bir font kopyalarken çoğu fontun telif hakkı bulunduğunu unutmayın. Önceden bir fontun lisansını bulup, başka bir makineye özgürce aktarılabileceğini doğrulayın. Font verisi None ise veya bu font zaten gömülü ise ArgumentException fırlatılabilir |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Embedded font ekler<br/>            Herhangi bir font kopyalarken çoğu fontun telif hakkı bulunduğunu unutmayın. Önceden bir fontun lisansını bulup, başka bir makineye özgürce aktarılabileceğini doğrulayın. Font verisi None ise veya bu font zaten gömülü ise ArgumentException fırlatılabilir |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/tr/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Sunumda fontu değiştir |
| [`replace_font(self, subst_rule)`](/slides/python-net/tr/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Sunumda fontu, [`FontSubstRule`](/slides/python-net/tr/aspose.slides/fontsubstrule) içinde sağlanan bilgiler kullanılarak değiştir |
| [`replace_font(self, subst_rules)`](/slides/python-net/tr/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Sunumda fontu, [`FontSubstRule`](/slides/python-net/tr/aspose.slides/fontsubstrule) koleksiyonunda sağlanan bilgiler kullanılarak değiştir |
| [`get_fonts(self)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_fonts/#) | Sunumda kullanılan fontları döndürür |
| [`get_embedded_fonts(self)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_embedded_fonts/#) | Sunumda gömülü fontları döndürür |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/tr/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Gömülü fontu kaldırır |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Belirtilen bir font stili ve font verisi için font verisini temsil eden bayt dizisini alır. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Verilen bayt dizisi ve font adından bir fontun gömme seviyesini belirler. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)