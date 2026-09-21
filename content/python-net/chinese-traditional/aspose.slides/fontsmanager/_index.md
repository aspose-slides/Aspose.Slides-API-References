---
title: FontsManager class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/fontsmanager/
---
## FontsManager 類別

在簡報中管理字型。

FontsManager 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/font_subst_rule_list/) | 在渲染時使用的字型替代項。<br/>            讀/寫 [`IFontSubstRuleCollection`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrulecollection)。 |
| [`font_fall_back_rules_collection`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | 代表使用者的 FontFallBack 規則集合，用於管理字型集合以透過回退功能正確替代。<br/>            讀/寫 [`IFontFallBackRulesCollection`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrulescollection)。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/get_substitutions/#) | 取得簡報渲染時將被取代的字型資訊。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/get_substitutions/#listint) | 取得在指定投影片渲染期間將被取代的字型資訊。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 新增嵌入字型<br/>            請注意，複製任何字型時大多數字型都有版權。首先先取得字型的授權，確認它們可以自由轉移至其他機器。如果 font data 為 None 或此字型已經嵌入，將拋出 ArgumentException。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 新增嵌入字型<br/>            請注意，複製任何字型時大多數字型都有版權。首先先取得字型的授權，確認它們可以自由轉移至其他機器。如果 font data 為 None 或此字型已經嵌入，將拋出 ArgumentException。 |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | 在簡報中取代字型 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | 使用 [`FontSubstRule`](/slides/python-net/zh-hant/aspose.slides/fontsubstrule) 提供的資訊在簡報中取代字型 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`FontSubstRule`](/slides/python-net/zh-hant/aspose.slides/fontsubstrule) 集合提供的資訊在簡報中取代字型 |
| [`get_fonts(self)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/get_fonts/#) | 回傳簡報中使用的字型 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/get_embedded_fonts/#) | 回傳簡報中嵌入的字型 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字型 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 取得表示指定字型樣式與字型資料之字型資料的位元組陣列。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh-hant/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | 依給定的位元組陣列與字型名稱判斷字型的嵌入層級。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)