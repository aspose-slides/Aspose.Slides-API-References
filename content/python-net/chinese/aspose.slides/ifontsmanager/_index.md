---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ifontsmanager/
---
## IFontsManager 类

在演示文稿中管理字体。

IFontsManager 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh/aspose.slides/ifontsmanager/font_subst_rule_list/) | 在渲染时使用的字体替代<br/>            读/写 [`IFontSubstRuleCollection`](/slides/python-net/zh/aspose.slides/ifontsubstrulecollection)。 |
| [`font_fall_back_rules_collection`](/slides/python-net/zh/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | 表示用户的 FontFallBack 规则集合，用于通过回退功能对字体集合进行适当替换<br/>            读/写 [`IFontFallBackRulesCollection`](/slides/python-net/zh/aspose.slides/ifontfallbackrulescollection)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_substitutions/#) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_substitutions/#listint) | 获取在指定幻灯片渲染期间将被替换的字体信息。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 添加嵌入式字体。<br/>            请记住，在复制任何字体时，大多数字体受版权保护。请先查找字体的许可证<br/>            并确认它们可以自由转移到另一台机器。如果 font data 为 None 或此字体已嵌入，则可能抛出 ArgumentException。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 添加嵌入式字体<br/>            请记住，在添加任何字体时，大多数字体受版权保护。请先查找字体的许可证<br/>            并确认它们可以自由转移到另一台机器。如果 font data 为 None 或此字体已嵌入，则可能抛出 ArgumentException。 |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | 在演示文稿中替换字体 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | 使用 [`IFontSubstRule`](/slides/python-net/zh/aspose.slides/ifontsubstrule) 中提供的信息在演示文稿中替换字体 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`IFontSubstRule`](/slides/python-net/zh/aspose.slides/ifontsubstrule) 集合中提供的信息在演示文稿中替换字体 |
| [`get_fonts(self)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_fonts/#) | 返回演示文稿中使用的字体 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_embedded_fonts/#) | 返回嵌入在演示文稿中的字体 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字体 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 检索表示指定字体样式和字体数据的字节数组 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | 根据给定的字节数组和字体名称确定字体的嵌入级别 |


### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)