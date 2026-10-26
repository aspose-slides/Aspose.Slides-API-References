---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/notesslide/
---
## NotesSlide 类

表示演示文稿中的备注幻灯片。

**继承:**[`NotesSlide`](/slides/python-net/zh/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)

NotesSlide 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/notesslide/shapes/) | 返回幻灯片的形状。<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh/aspose.slides/notesslide/controls/) | 返回幻灯片上 ActiveX 控件的集合。<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh/aspose.slides/notesslide/name/) | 返回或设置幻灯片的名称。<br/>            读/写 **str**。 |
| [`slide_id`](/slides/python-net/zh/aspose.slides/notesslide/slide_id/) | 返回幻灯片的 ID。<br/>            只读 **int**。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/notesslide/custom_data/) | 返回幻灯片的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh/aspose.slides/notesslide/timeline/) | 返回动画时间线对象。<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/notesslide/slide_show_transition/) | 返回 Transition 对象，其中包含关于<br/>            指定幻灯片在幻灯片放映期间如何前进的信息。<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh/aspose.slides/notesslide/background/) | 返回幻灯片的背景。<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/notesslide/hyperlink_queries/) | 提供对包含的超链接的便捷访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/notesslide/show_master_shapes/) | 指定母版幻灯片上的形状是否应在幻灯片上显示。<br/>            读/写 **bool**。 |
| [`presentation`](/slides/python-net/zh/aspose.slides/notesslide/presentation/) | 返回 IPresentation 接口。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/notesslide/header_footer_manager/) | 返回备注幻灯片的 HeaderFooter 管理器。<br/>            只读 [`INotesSlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/inotesslideheaderfootermanager)。 |
| [`notes_text_frame`](/slides/python-net/zh/aspose.slides/notesslide/notes_text_frame/) | 如果存在，则返回包含备注文本的 TextFrame。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe)。 |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/notesslide/theme_manager/) | 返回覆盖主题管理器。<br/>            只读 [`IOverrideThemeManager`](/slides/python-net/zh/aspose.slides.theme/ioverridethememanager)。 |
| [`parent_slide`](/slides/python-net/zh/aspose.slides/notesslide/parent_slide/) | 返回父幻灯片。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/notesslide/slide/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/notesslide/join_portions_with_same_formatting/#) | 在所有可接受的形状的所有段落中，将具有相同格式的运行合并。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | 在所有可接受的形状中的所有段落里，将具有相同格式的运行合并。 |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/notesslide/equals/#ibaseslide) | 确定两个 IBaseSlide 实例是否相等。<br/>            返回值基于幻灯片的结构和静态内容计算。<br/>            当所有形状、样式、文本、动画以及其他设置等都相等时，两个幻灯片被视为相等。比较时不考虑唯一标识符值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/notesslide/create_theme_effective/#) | 返回此幻灯片的有效主题。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/notesslide/find_shape_by_alt_text/#str) | 查找具有指定替代文本的形状的首次出现。 |

### 另见
* 类 [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)
* 类 [`NotesSlide`](/slides/python-net/zh/aspose.slides/notesslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)