---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ifontsmanager/
---
## IFontsManager 类

管理整个演示文稿中的字体。

IFontsManager 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/zh/aspose.slides/ifontsmanager/font_subst_rule_list/) | 在渲染时使用的字体替代<br/>            读/写 [`IFontSubstRuleCollection`](/slides/python-net/zh/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/zh/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | 表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体集合，以实现正确的替代<br/>            读/写 [`IFontFallBackRulesCollection`](/slides/python-net/zh/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/zh/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | 指定在具有相同字体名称和样式的嵌入字体上是否应优先使用已注册字体。<br/>            启用后，匹配的嵌入字体将在导出期间临时替换为相应的已注册字体。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_substitutions/#) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [`get_substitutions(self, slides)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_substitutions/#listint) | 获取在指定幻灯片渲染期间将被替换的字体信息。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 添加嵌入字体。<br/>            请记住，复制任何字体时大多数字体都有版权。首先在事先查找字体的许可证，并验证它们是否可以自由转移到另一台机器。如果 font data 为 None 或该字体已嵌入，则会抛出 ArgumentException。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/zh/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 添加嵌入字体<br/>            请记住，添加任何字体时大多数字体都有版权。首先在事先查找字体的许可证，并验证它们是否可以自由转移到另一台机器。如果 font data 为 None 或该字体已嵌入，则会抛出 ArgumentException。 |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/zh/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | 在演示文稿中替换字体 |
| [`replace_font(self, subst_rule)`](/slides/python-net/zh/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | 使用 [`IFontSubstRule`](/slides/python-net/zh/aspose.slides/ifontsubstrule) 中提供的信息在演示文稿中替换字体 |
| [`replace_font(self, subst_rules)`](/slides/python-net/zh/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | 使用 [`IFontSubstRule`](/slides/python-net/zh/aspose.slides/ifontsubstrule) 集合中提供的信息在演示文稿中替换字体 |
| [`get_fonts(self)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_fonts/#) | 返回演示文稿中使用的字体 |
| [`get_embedded_fonts(self)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_embedded_fonts/#) | 返回嵌入在演示文稿中的字体 |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/zh/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | 移除嵌入的字体 |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 检索表示指定字体样式和字体数据的字节数组。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/zh/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | 根据给定的字节数组和字体名称确定字体的嵌入级别。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)