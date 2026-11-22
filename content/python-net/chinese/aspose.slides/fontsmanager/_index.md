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

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh/aspose.slides/fontsmanager/font_subst_rule_list/) | 在渲染时使用的字体替代。<br/>            可读写 [`IFontSubstRuleCollection`](/slides/python-net/zh/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/zh/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | 表示用户的 FontFallBack 规则集合，用于管理字体集合以通过回退功能进行适当替换。<br/>            可读写 [`IFontFallBackRulesCollection`](/slides/python-net/zh/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/zh/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | 指定是否应优先使用已注册的字体而不是具有相同字体名称和样式的嵌入字体。<br/>            启用后，匹配的嵌入字体会在导出时暂时被相应的已注册字体替换。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_substitutions/#) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_substitutions/#listint) | 获取在指定幻灯片渲染期间将被替换的字体信息。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 添加嵌入字体<br/>            请注意，复制任何字体时，大多数字体都有版权。首先提前查找字体的许可证，并确认它们可以自由转移到另一台机器。如果字体数据为 None 或该字体已嵌入，则会抛出 ArgumentException。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 添加嵌入字体<br/>            请注意，复制任何字体时，大多数字体都有版权。首先提前查找字体的许可证，并确认它们可以自由转移到另一台机器。如果字体数据为 None 或该字体已嵌入，则会抛出 ArgumentException。 |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | 替换演示文稿中的字体 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | 使用 [`FontSubstRule`](/slides/python-net/zh/aspose.slides/fontsubstrule) 中提供的信息替换演示文稿中的字体 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`FontSubstRule`](/slides/python-net/zh/aspose.slides/fontsubstrule) 集合中提供的信息替换演示文稿中的字体 |
| [`get_fonts(self)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_fonts/#) | 返回演示文稿中使用的字体 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_embedded_fonts/#) | 返回嵌入在演示文稿中的字体 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字体 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 检索表示指定字体样式和字体数据的字节数组。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | 根据给定的字节数组和字体名称确定字体的嵌入级别。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)