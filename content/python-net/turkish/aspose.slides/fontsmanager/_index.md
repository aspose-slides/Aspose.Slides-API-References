---
title: FontsManager class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/fontsmanager/
---
## FontsManager sınıfı

Sunum boyunca fontları yönetir.

FontsManager türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/tr/aspose.slides/fontsmanager/font_subst_rule_list/) | Render ederken kullanılacak font ikameleri.<br/>            Okuma/Yazma [`IFontSubstRuleCollection`](/slides/python-net/tr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/tr/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Kullanıcının font koleksiyonlarını uygun ikameler için yöneten FontFallBack kurallarının koleksiyonunu temsil eder<br/>            Okuma/Yazma [`IFontFallBackRulesCollection`](/slides/python-net/tr/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/tr/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Aynı font adı ve stiline sahip gömülü fontlara göre kayıtlı fontların tercih edilip edilmeyeceğini belirtir.<br/>            Etkinleştirildiğinde, eşleşen gömülü fontlar dışa aktarım sırasında geçici olarak ilgili kayıtlı fontlarla değiştirilir. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_substitutions/#) | Sunumun render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır. |
| [`get_substitutions(self, slides)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_substitutions/#listint) | Belirtilen slaytların render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Gömülü font ekler<br/>            Fontları kopyalarken çoğu fontun telif hakkına sahip olduğunu unutmayın. Önceden bir fontun lisansını bulun ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. Font verisi None ise veya bu font zaten gömülü ise ArgumentException alınabilir |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/tr/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Gömülü font ekler<br/>            Fontları kopyalarken çoğu fontun telif hakkına sahip olduğunu unutmayın. Önceden bir fontun lisansını bulun ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. Font verisi None ise veya bu font zaten gömülü ise ArgumentException alınabilir |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/tr/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Sunumda fontu değiştir |
| [`replace_font(self, subst_rule)`](/slides/python-net/tr/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Sunumda fontu [`FontSubstRule`](/slides/python-net/tr/aspose.slides/fontsubstrule) içinde verilen bilgilerle değiştir |
| [`replace_font(self, subst_rules)`](/slides/python-net/tr/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Sunumda fontu [`FontSubstRule`](/slides/python-net/tr/aspose.slides/fontsubstrule) koleksiyonunda sağlanan bilgilerle değiştir |
| [`get_fonts(self)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_fonts/#) | Sunumda kullanılan fontları döndürür |
| [`get_embedded_fonts(self)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_embedded_fonts/#) | Sunumda gömülü fontları döndürür |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/tr/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Gömülü fontu kaldırır |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Belirtilen bir font stili ve font verisi için font verisini temsil eden bayt dizisini alır. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/tr/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Verilen bayt dizisi ve font adından bir fontun gömme seviyesini belirler. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)