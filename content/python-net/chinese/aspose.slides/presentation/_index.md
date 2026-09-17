---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentation/
---
## Presentation 类

表示 Microsoft PowerPoint 演示文稿。

Presentation 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/presentation/__init__/#) | 此构造函数从头创建新的演示文稿。<br/>            创建的演示文稿包含一个空白幻灯片。 |
| [`__init__(self, load_options)`](/slides/python-net/zh/aspose.slides/presentation/__init__/#loadoptions) | 此构造函数从头创建新的演示文稿。<br/>            创建的演示文稿包含一个空白幻灯片。 |
| [`__init__(self, stream)`](/slides/python-net/zh/aspose.slides/presentation/__init__/#iorawiobase) | 此构造函数是读取现有 Presentation 的主要机制。 |
| [`__init__(self, stream, load_options)`](/slides/python-net/zh/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | 此构造函数是读取现有 Presentation 的主要机制。 |
| [`__init__(self, file)`](/slides/python-net/zh/aspose.slides/presentation/__init__/#str) | 此构造函数获取源文件路径，以便<br/>             读取演示文稿的内容。 |
| [`__init__(self, file, load_options)`](/slides/python-net/zh/aspose.slides/presentation/__init__/#str-loadoptions) | 此构造函数获取源文件路径，以便<br/>            读取演示文稿的内容。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`current_date_time`](/slides/python-net/zh/aspose.slides/presentation/current_date_time/) | 返回或设置用于替换 datetime 字段内容的日期和时间。<br/>            默认情况下为此 Presentation 对象创建的时间。<br/>            可读写 **System.DateTime**。 |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/presentation/header_footer_manager/) | 返回实际的 HeaderFooter 管理器。<br/>            只读 [`IPresentationHeaderFooterManager`](/slides/python-net/zh/aspose.slides/ipresentationheaderfootermanager)。 |
| [`protection_manager`](/slides/python-net/zh/aspose.slides/presentation/protection_manager/) | 获取此演示文稿的权限管理器。<br/>            只读 [`IProtectionManager`](/slides/python-net/zh/aspose.slides/iprotectionmanager)。 |
| [`slides`](/slides/python-net/zh/aspose.slides/presentation/slides/) | 返回演示文稿中定义的所有幻灯片的列表。<br/zh/>            只读 [`ISlideCollection`](/slides/python-net/zh/aspose.slides/islidecollection)。 |
| [`sections`](/slides/python-net/zh/aspose.slides/presentation/sections/) | 返回演示文稿中定义的所有幻灯片章节的列表。<br/>            只读 [`ISectionCollection`](/slides/python-net/zh/aspose.slides/isectioncollection)。 |
| [`slide_size`](/slides/python-net/zh/aspose.slides/presentation/slide_size/) | 返回幻灯片尺寸对象。<br/>            只读 [`ISlideSize`](/slides/python-net/zh/aspose.slides/islidesize)。 |
| [`notes_size`](/slides/python-net/zh/aspose.slides/presentation/notes_size/) | 返回备注幻灯片尺寸对象。<br/>            只读 [`INotesSize`](/slides/python-net/zh/aspose.slides/inotessize)。 |
| [`layout_slides`](/slides/python-net/zh/aspose.slides/presentation/layout_slides/) | 返回演示文稿中定义的所有版式幻灯片的列表。<br/>            只读 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/igloballayoutslidecollection)。 |
| [`masters`](/slides/python-net/zh/aspose.slides/presentation/masters/) | 返回演示文稿中定义的所有母版幻灯片的列表。<br/>            只读 [`IMasterSlideCollection`](/slides/python-net/zh/aspose.slides/imasterslidecollection)。 |
| [`master_notes_slide_manager`](/slides/python-net/zh/aspose.slides/presentation/master_notes_slide_manager/) | 返回备注母版管理器。<br/>            只读 [`IMasterNotesSlideManager`](/slides/python-net/zh/aspose.slides/imasternotesslidemanager)。 |
| [`master_handout_slide_manager`](/slides/python-net/zh/aspose.slides/presentation/master_handout_slide_manager/) | 返回讲义母版管理器。<br/>            只读 [`IMasterHandoutSlideManager`](/slides/python-net/zh/aspose.slides/imasterhandoutslidemanager)。 |
| [`fonts_manager`](/slides/python-net/zh/aspose.slides/presentation/fonts_manager/) | 返回字体管理器。<br/>            只读 [`IFontsManager`](/slides/python-net/zh/aspose.slides/ifontsmanager)。 |
| [`default_text_style`](/slides/python-net/zh/aspose.slides/presentation/default_text_style/) | 返回形状的默认文字样式。<br/>            只读 [`ITextStyle`](/slides/python-net/zh/aspose.slides/itextstyle)。 |
| [`comment_authors`](/slides/python-net/zh/aspose.slides/presentation/comment_authors/) | 返回评论作者的集合。<br/>            只读 [`ICommentAuthorCollection`](/slides/python-net/zh/aspose.slides/icommentauthorcollection)。 |
| [`document_properties`](/slides/python-net/zh/aspose.slides/presentation/document_properties/) | 返回 DocumentProperties 对象，其中包含标准和自定义文档属性。<br/>            只读 [`IDocumentProperties`](/slides/python-net/zh/aspose.slides/idocumentproperties)。 |
| [`images`](/slides/python-net/zh/aspose.slides/presentation/images/) | 返回演示文稿中所有图像的集合。<br/>            只读 [`IImageCollection`](/slides/python-net/zh/aspose.slides/iimagecollection)。 |
| [`audios`](/slides/python-net/zh/aspose.slides/presentation/audios/) | 返回演示文稿中所有嵌入式音频文件的集合。<br/>            只读 [`IAudioCollection`](/slides/python-net/zh/aspose.slides/iaudiocollection)。 |
| [`videos`](/slides/python-net/zh/aspose.slides/presentation/videos/) | 返回演示文稿中所有嵌入式视频文件的集合。<br/>            只读 [`IVideoCollection`](/slides/python-net/zh/aspose.slides/ivideocollection)。 |
| [`slide_show_settings`](/slides/python-net/zh/aspose.slides/presentation/slide_show_settings/) | 返回演示文稿的幻灯片放映设置。 |
| [`digital_signatures`](/slides/python-net/zh/aspose.slides/presentation/digital_signatures/) | 返回用于签署演示文稿的签名集合。<br/>            只读 [`IDigitalSignatureCollection`](/slides/python-net/zh/aspose.slides/idigitalsignaturecollection)。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/presentation/custom_data/) | 返回演示文稿的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`all_custom_xml_parts`](/slides/python-net/zh/aspose.slides/presentation/all_custom_xml_parts/) | 返回演示文稿中的所有自定义数据部分。<br/>            只读 [`ICustomXmlPart`](/slides/python-net/zh/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/zh/aspose.slides/presentation/vba_project/) | 获取或设置包含演示文稿宏的 VBA 项目。<br/>            可读写 [`IVbaProject`](/slides/python-net/zh/aspose.slides.vba/ivbaproject)。 |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/presentation/hyperlink_queries/) | 提供对所有演示文稿幻灯片（不包括母版、版式、备注幻灯片）中包含的超链接的便捷访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries)。 |
| [`view_properties`](/slides/python-net/zh/aspose.slides/presentation/view_properties/) | 获取整个演示文稿的视图属性。<br/>            只读 [`IViewProperties`](/slides/python-net/zh/aspose.slides/iviewproperties)。 |
| [`first_slide_number`](/slides/python-net/zh/aspose.slides/presentation/first_slide_number/) | 表示演示文稿中的第一页幻灯片编号 |
| [`sensitivity_labels`](/slides/python-net/zh/aspose.slides/presentation/sensitivity_labels/) | 返回应用于演示文稿文档的敏感度标签集合。<br/>            只读 [`ISensitivityLabelCollection`](/slides/python-net/zh/aspose.slides/isensitivitylabelcollection)。 |
| [`source_format`](/slides/python-net/zh/aspose.slides/presentation/source_format/) | 返回有关演示文稿加载自何种格式的信息。<br/>            只读 [`SourceFormat`](/slides/python-net/zh/aspose.slides/sourceformat)。 |
| [`master_theme`](/slides/python-net/zh/aspose.slides/presentation/master_theme/) | 返回母版主题。<br/>            只读 [`IMasterTheme`](/slides/python-net/zh/aspose.slides.theme/imastertheme)。 |
| [`presentation`](/slides/python-net/zh/aspose.slides/presentation/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/zh/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | 将演示文稿的所有幻灯片保存为指定格式的文件。 |
| [`save(self, stream, format)`](/slides/python-net/zh/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | 将演示文稿的所有幻灯片保存到指定格式的流。 |
| [`save(self, fname, format, options)`](/slides/python-net/zh/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/zh/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的所有幻灯片保存到指定格式的流，并使用附加选项。 |
| [`save(self, options)`](/slides/python-net/zh/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | 将演示文稿的所有幻灯片保存为表示 XAML 标记的文件集合。 |
| [`save(self, fname, slides, format)`](/slides/python-net/zh/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | 将演示文稿的指定幻灯片保存为保留页码的指定格式文件。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/zh/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的指定幻灯片保存为保留页码的指定格式文件。 |
| [`save(self, stream, slides, format)`](/slides/python-net/zh/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 将演示文稿的指定幻灯片保存到保留页码的指定格式流中。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/zh/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的指定幻灯片保存到保留页码的指定格式流中。 |
| [`get_images(self, options)`](/slides/python-net/zh/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | 返回演示文稿所有幻灯片的 Image 对象。 |
| [`get_images(self, options, slides)`](/slides/python-net/zh/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | 返回演示文稿指定幻灯片的 Thumbnail Image 对象。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | 返回演示文稿所有幻灯片的 Thumbnail Image 对象，使用自定义缩放。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | 返回演示文稿指定幻灯片的 Thumbnail Image 对象，使用自定义缩放。 |
| [`get_images(self, options, image_size)`](/slides/python-net/zh/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | 返回演示文稿所有幻灯片的 Thumbnail Image 对象，使用指定尺寸。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/zh/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | 返回演示文稿指定幻灯片的 Thumbnail Image 对象，使用指定尺寸。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/zh/aspose.slides/presentation/get_slide_by_id/#int) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/presentation/join_portions_with_same_formatting/#) | 在所有幻灯片的所有可接受形状中的所有段落中，合并具有相同格式的运行。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 将指定文本的所有出现替换为另一个指定文本。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh/aspose.slides/presentation/replace_regex/#str-str) | 将正则表达式的所有匹配项替换为指定字符串。 |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)