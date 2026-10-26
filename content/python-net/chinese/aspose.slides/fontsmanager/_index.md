---
title: FontsManager class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/fontsmanager/
---
## FontsManager 类

管理整个演示文稿中的字体。

FontsManager 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh/aspose.slides/fontsmanager/font_subst_rule_list/) | 在渲染时使用的字体替换。<br/>            读/写 [`IFontSubstRuleCollection`](/slides/python-net/zh/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/zh/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | 表示用户用于通过回退功能正确替换字体的 FontFallBack 规则集合。<br/>            读/写 [`IFontFallBackRulesCollection`](/slides/python-net/zh/aspose.slides/ifontfallbackrulescollection). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_substitutions/#) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_substitutions/#listint) | 获取在指定幻灯片渲染期间将被替换的字体信息。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 添加嵌入式字体<br/>            在复制任何字体时请记住，大多数字体受版权保护。首先提前查找字体的许可证，并确认它们可以自由转移到另一台机器上。An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 添加嵌入式字体<br/>            在复制任何字体时请记住，大多数字体受版权保护。首先提前查找字体的许可证，并确认它们可以自由转移到另一台机器上。An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | 在演示文稿中替换字体 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | 使用 [`FontSubstRule`](/slides/python-net/zh/aspose.slides/fontsubstrule) 提供的信息在演示文稿中替换字体 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`FontSubstRule`](/slides/python-net/zh/aspose.slides/fontsubstrule) 集合提供的信息在演示文稿中替换字体 |
| [`get_fonts(self)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_fonts/#) | 返回在演示文稿中使用的字体 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_embedded_fonts/#) | 返回在演示文稿中嵌入的字体 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字体 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 检索表示指定字体样式和字体数据的字节数组。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | 从给定的字节数组和字体名称确定字体的嵌入级别。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)