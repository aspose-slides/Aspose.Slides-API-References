---
title: IBaseSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ibaseslide/
---
## IBaseSlide 类

表示所有幻灯片类型的通用数据。

IBaseSlide 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/ibaseslide/shapes/) | 返回幻灯片的形状。<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh/aspose.slides/ibaseslide/controls/) | 返回幻灯片上 ActiveX 控件的集合。<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh/aspose.slides/ibaseslide/name/) | 返回或设置幻灯片的名称。<br/>            读写 **str**。 |
| [`slide_id`](/slides/python-net/zh/aspose.slides/ibaseslide/slide_id/) | 返回幻灯片的 ID。<br/>            只读 **int**。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/ibaseslide/custom_data/) | 返回幻灯片的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh/aspose.slides/ibaseslide/timeline/) | 返回动画时间轴对象。<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/ibaseslide/slide_show_transition/) | 返回 TransitionEx 对象，该对象包含关于<br/>            指定幻灯片在幻灯片放映期间如何前进的信息。<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh/aspose.slides/ibaseslide/background/) | 返回幻灯片的背景。<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/ibaseslide/hyperlink_queries/) | 提供对包含的超链接的便捷访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/ibaseslide/show_master_shapes/) | 指定是否在幻灯片上显示母版幻灯片上的形状。<br/>            对于母版幻灯片本身，此属性始终返回 `false`。<br/>            读写 **bool**。 |
| [`slide`](/slides/python-net/zh/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/ibaseslide/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | 查找具有指定替代文本的形状的首次出现。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | 在所有可接受的形状的所有段落中合并具有相同格式的文本运行。 |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/ibaseslide/equals/#ibaseslide) | 确定两个 IBaseSlide 实例是否相等。<br/>            返回值基于幻灯片的结构和静态内容计算。<br/>            如果所有形状、样式、文本、动画及其他设置等全部相等，则两个幻灯片相等。比较时不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### 参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)