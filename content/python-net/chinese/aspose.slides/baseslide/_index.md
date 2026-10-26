---
title: BaseSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/baseslide/
---
## BaseSlide 类

表示所有幻灯片类型的通用数据。

BaseSlide 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/baseslide/shapes/) | 返回幻灯片的形状。<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh/aspose.slides/baseslide/controls/) | 返回幻灯片上 ActiveX 控件的集合。<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh/aspose.slides/baseslide/name/) | 返回或设置幻灯片的名称。<br/>            读写 **str**。 |
| [`slide_id`](/slides/python-net/zh/aspose.slides/baseslide/slide_id/) | 返回幻灯片的 ID。<br/>            只读 **int**。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/baseslide/custom_data/) | 返回幻灯片的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh/aspose.slides/baseslide/timeline/) | 返回动画时间轴对象。<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/baseslide/slide_show_transition/) | 返回 Transition 对象，其中包含有关指定幻灯片在放映期间如何前进的信息。<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh/aspose.slides/baseslide/background/) | 返回幻灯片的背景。<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/baseslide/hyperlink_queries/) | 提供对包含的超链接的便捷访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/baseslide/show_master_shapes/) | 指定主幻灯片上的形状是否应在幻灯片上显示。<br/>            对于主幻灯片本身，此属性始终返回 `false`。<br/>            读写 **bool**。 |
| [`presentation`](/slides/python-net/zh/aspose.slides/baseslide/presentation/) | 返回 IPresentation 接口。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/baseslide/slide/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/baseslide/join_portions_with_same_formatting/#) | 在所有可接受的形状的所有段落中，将具有相同格式的 runs 合并。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | 在所有可接受的形状的所有段落中，将具有相同格式的 runs 合并。 |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/baseslide/equals/#ibaseslide) | 确定两个 IBaseSlide 实例是否相等。<br/>            返回值基于幻灯片的结构和静态内容进行计算。<br/>            如果所有形状、样式、文本、动画和其他设置等全部相等，则两个幻灯片相等。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/baseslide/create_theme_effective/#) | 返回此幻灯片的有效主题。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/baseslide/find_shape_by_alt_text/#str) | 查找具有指定替代文本的形状的首次出现。 |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)