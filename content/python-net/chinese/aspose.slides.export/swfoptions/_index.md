---
title: SwfOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/swfoptions/
---
## SwfOptions 类

提供控制演示文稿以 Swf 格式保存方式的选项。

**继承:**[`SwfOptions`](/slides/python-net/zh/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

SwfOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 说明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/swfoptions/__init__/#) | 默认构造函数。 |

## 属性

| 属性 | 说明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/swfoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/swfoptions/progress_callback/) | 表示用于以百分比保存进度更新的回调对象。<br/>            请参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/swfoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读/写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/swfoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/swfoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。 <br/>            读/写 **bool**. 默认值为 **false** . |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_hidden_slides/) | 指定生成的文档是否应包含隐藏幻灯片。<br/>            默认值为 `false`. |
| [`compressed`](/slides/python-net/zh/aspose.slides.export/swfoptions/compressed/) | 指定生成的 SWF 文档是否应被压缩。<br/>            默认值为 `true`. |
| [`viewer_included`](/slides/python-net/zh/aspose.slides.export/swfoptions/viewer_included/) | 指定生成的 SWF 文档是否应包含集成的文档查看器。<br/>            默认值为 `true`. |
| [`show_page_border`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_page_border/) | 指定是否应显示页面周围的边框。默认值为 true. |
| [`show_full_screen`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_full_screen/) | 显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true. |
| [`show_page_stepper`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_page_stepper/) | 显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true. |
| [`show_search`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_search/) | 显示/隐藏搜索区域。可在 flashvars 中覆盖。默认值为 true. |
| [`show_top_pane`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_top_pane/) | 显示/隐藏整个顶部面板。可在 flashvars 中覆盖。默认值为 true. |
| [`show_bottom_pane`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_bottom_pane/) | 显示/隐藏底部面板。可在 flashvars 中覆盖。默认值为 true. |
| [`show_left_pane`](/slides/python-net/zh/aspose.slides.export/swfoptions/show_left_pane/) | 显示/隐藏左侧面板。可在 flashvars 中覆盖。默认值为 true. |
| [`start_open_left_pane`](/slides/python-net/zh/aspose.slides.export/swfoptions/start_open_left_pane/) | 以打开的左侧面板启动。可在 flashvars 中覆盖。默认值为 false. |
| [`enable_context_menu`](/slides/python-net/zh/aspose.slides.export/swfoptions/enable_context_menu/) | 启用/禁用上下文菜单。默认值为 true. |
| [`logo_image_bytes`](/slides/python-net/zh/aspose.slides.export/swfoptions/logo_image_bytes/) | 将在查看器右上角显示为徽标的图像。<br/>            图像应为 32x64 像素的 PNG 图像，否则徽标可能显示不正确。 |
| [`logo_link`](/slides/python-net/zh/aspose.slides.export/swfoptions/logo_link/) | 获取或设置徽标的完整超链接地址。<br/>            仅在指定了 [`SwfOptions.logo_image_bytes`](/slides/python-net/zh/aspose.slides.export/swfoptions/logo_image_bytes) 时有效。 |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/swfoptions/jpeg_quality/) | 指定 JPEG 图像的质量。<br/>            默认值为 95. |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/swfoptions/slides_layout_options/) | 获取或设置在导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。<br/>            此属性不支持分配类型为 [`HandoutLayoutingOptions`](/slides/python-net/zh/aspose.slides.export/handoutlayoutingoptions) 的对象 |

### 另见
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 类 [`SwfOptions`](/slides/python-net/zh/aspose.slides.export/swfoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)