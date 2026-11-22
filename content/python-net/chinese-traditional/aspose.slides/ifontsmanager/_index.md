---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ifontsmanager/
---
## IFontsManager 類別

管理簡報中的字型。

IFontsManager 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/font_subst_rule_list/) | 渲染時使用的字型替代<br/>            讀/寫 [`IFontSubstRuleCollection`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | 代表使用者的 FontFallBack 規則集合，用於透過回退功能管理字型集合的正確替代<br/>            讀/寫 [`IFontFallBackRulesCollection`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | 指定是否在字型名稱和樣式相同的情況下，優先使用已註冊的字型而非嵌入的字型。<br/>            啟用時，匹配的嵌入字型將在匯出期間暫時被相應的已註冊字型取代。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_substitutions/#) | 取得有關在簡報渲染時將被替換的字型資訊。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_substitutions/#listint) | 取得在指定投影片渲染期間將被替換的字型資訊。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 新增嵌入字型。<br/>            請記住，複製任何字型時，大多數字型都有版權。請先找出字型的授權許可，並確認它們可以自由轉移至其他機器。如果字型資料為 None 或此字型已嵌入，將拋出 ArgumentException。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 新增嵌入字型。<br/>            請記住，加入任何字型時，大多數字型都有版權。請先找出字型的授權許可，並確認它們可以自由轉移至其他機器。如果字型資料為 None 或此字型已嵌入，將拋出 ArgumentException。 |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | 在簡報中替換字型 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | 使用 [`IFontSubstRule`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrule) 中提供的資訊在簡報中替換字型 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`IFontSubstRule`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrule) 集合中提供的資訊在簡報中替換字型 |
| [`get_fonts(self)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_fonts/#) | 傳回簡報中使用的字型 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_embedded_fonts/#) | 傳回簡報中嵌入的字型 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字型 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 取得表示指定字型樣式和字型資料的位元組陣列。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | 根據給定的位元組陣列和字型名稱判斷字型的嵌入層級。 |

### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)