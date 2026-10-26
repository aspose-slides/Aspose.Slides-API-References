---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ifontsmanager/
---
## IFontsManager 類別

在簡報中管理字型。

IFontsManager 型別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/font_subst_rule_list/) | 在呈現時使用的字型替代<br/>            讀寫 [`IFontSubstRuleCollection`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | 代表使用者的 FontFallBack 規則集合，用於透過備援功能管理字型集合以正確替代<br/>            讀寫 [`IFontFallBackRulesCollection`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrulescollection). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_substitutions/#) | 取得有關在簡報呈現時將被取代的字型資訊。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_substitutions/#listint) | 取得有關在指定投影片呈現時將被取代的字型資訊。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 新增嵌入字型。<br/>            複製任何字型時請注意，大多數字型受版權保護。請先取得字型的授權，並確認可自由轉移至其他機器。如果 font data 為 None 或此字型已嵌入，將拋出 ArgumentException |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 新增嵌入字型<br/>            新增任何字型時請注意，大多數字型受版權保護。請先取得字型的授權，並確認可自由轉移至其他機器。如果 font data 為 None 或此字型已嵌入，將拋出 ArgumentException |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | 在簡報中取代字型 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | 使用 [`IFontSubstRule`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrule) 中提供的資訊在簡報中取代字型 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`IFontSubstRule`](/slides/python-net/zh-hant/aspose.slides/ifontsubstrule) 集合中提供的資訊在簡報中取代字型 |
| [`get_fonts(self)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_fonts/#) | 返回簡報中使用的字型 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_embedded_fonts/#) | 返回嵌入於簡報中的字型 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字型 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 取得指定字型樣式和字型資料的字型資料位元組陣列。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | 從給定的位元組陣列與字型名稱判斷字型的嵌入等級。 |


### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)