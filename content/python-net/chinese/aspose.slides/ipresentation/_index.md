---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ipresentation/
---
## IPresentation 类

演示文档

IPresentation 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/zh/aspose.slides/ipresentation/current_date_time/) | 返回或设置日期和时间，这将替代 datetime 字段的内容。<br/>            此 Presentation 对象创建时的时间，默认情况下。<br/>            读/写 **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/ipresentation/header_footer_manager/) | 返回演示文稿的 HeaderFooter 管理器。<br/>            只读 [`IPresentationHeaderFooterManager`](/slides/python-net/zh/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/zh/aspose.slides/ipresentation/protection_manager/) | 获取此演示文稿的权限管理器。 <br/>            只读 [`IProtectionManager`](/slides/python-net/zh/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/zh/aspose.slides/ipresentation/slides/) | 返回演示文稿中定义的所有幻灯片的列表。<br/zh/>            只读 [`ISlideCollection`](/slides/python-net/zh/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/zh/aspose.slides/ipresentation/sections/) | 返回演示文稿中定义的所有幻灯片章节的列表。<br/>            只读 [`ISectionCollection`](/slides/python-net/zh/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/zh/aspose.slides/ipresentation/slide_size/) | 返回幻灯片大小对象。<br/>            只读 [`ISlideSize`](/slides/python-net/zh/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/zh/aspose.slides/ipresentation/notes_size/) | 返回备注幻灯片大小对象。<br/>            只读 [`INotesSize`](/slides/python-net/zh/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/zh/aspose.slides/ipresentation/layout_slides/) | 返回演示文稿中定义的所有布局幻灯片的列表。<br/>            只读 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/zh/aspose.slides/ipresentation/masters/) | 返回演示文稿中定义的所有母版幻灯片的列表。<br/>            只读 [`IMasterSlideCollection`](/slides/python-net/zh/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/zh/aspose.slides/ipresentation/master_notes_slide_manager/) | 返回备注母版管理器。<br/>            只读 [`IMasterNotesSlideManager`](/slides/python-net/zh/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/zh/aspose.slides/ipresentation/master_handout_slide_manager/) | 返回讲义母版管理器。<br/>            只读 [`IMasterHandoutSlideManager`](/slides/python-net/zh/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/zh/aspose.slides/ipresentation/fonts_manager/) | 返回字体管理器。<br/>            只读 [`IFontsManager`](/slides/python-net/zh/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/zh/aspose.slides/ipresentation/default_text_style/) | 返回形状的默认文本样式。<br/>            只读 [`ITextStyle`](/slides/python-net/zh/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/zh/aspose.slides/ipresentation/comment_authors/) | 返回评论作者的集合。<br/>            只读 [`ICommentAuthorCollection`](/slides/python-net/zh/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/zh/aspose.slides/ipresentation/document_properties/) | 返回 DocumentProperties 对象，其中包含标准和自定义文档属性。<br/>            只读 [`IDocumentProperties`](/slides/python-net/zh/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/zh/aspose.slides/ipresentation/images/) | 返回演示文稿中所有图像的集合。<br/>            只读 [`IImageCollection`](/slides/python-net/zh/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/zh/aspose.slides/ipresentation/audios/) | 返回演示文稿中所有嵌入音频文件的集合。<br/>            只读 [`IAudioCollection`](/slides/python-net/zh/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/zh/aspose.slides/ipresentation/videos/) | 返回演示文稿中所有嵌入视频文件的集合。<br/>            只读 [`IVideoCollection`](/slides/python-net/zh/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/ipresentation/custom_data/) | 返回演示文稿的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/zh/aspose.slides/ipresentation/vba_project/) | 获取包含演示宏的 VBA 项目。<br/>            读/写 [`IVbaProject`](/slides/python-net/zh/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/zh/aspose.slides/ipresentation/source_format/) | 返回关于演示文稿加载自何种格式的信息。<br/>            只读 [`IPresentation.source_format`](/slides/python-net/zh/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/zh/aspose.slides/ipresentation/master_theme/) | 返回演示文稿的母版主题。<br/>            只读 [`IMasterTheme`](/slides/python-net/zh/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/ipresentation/hyperlink_queries/) | 提供对所有演示幻灯片中包含的超链接的便捷访问（不包括母版、布局、备注幻灯片）。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/zh/aspose.slides/ipresentation/view_properties/) | 获取演示文稿范围的视图属性。<br/>            只读 [`IViewProperties`](/slides/python-net/zh/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/zh/aspose.slides/ipresentation/first_slide_number/) | 表示演示文稿中的第一页幻灯片编号。<br/>            读/写 **int**. |
| [`all_custom_xml_parts`](/slides/python-net/zh/aspose.slides/ipresentation/all_custom_xml_parts/) | 返回演示文稿中的所有自定义数据部分。<br/>            只读 [`ICustomXmlPart`](/slides/python-net/zh/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/zh/aspose.slides/ipresentation/digital_signatures/) | 返回用于签署演示文稿的签名集合。<br/>            只读 [`IDigitalSignatureCollection`](/slides/python-net/zh/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/zh/aspose.slides/ipresentation/sensitivity_labels/) | 返回应用于演示文稿的敏感度标签集合。<br/>            只读 [`ISensitivityLabelCollection`](/slides/python-net/zh/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/zh/aspose.slides/ipresentation/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | 将演示文稿的所有幻灯片保存为指定格式的文件。 |
| [`save(self, stream, format)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | 将演示文稿的所有幻灯片保存到指定格式的流中。 |
| [`save(self, fname, format, options)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用其他选项。 |
| [`save(self, stream, format, options)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的所有幻灯片保存到指定格式的流中，并使用其他选项。 |
| [`save(self, fname, slides, format)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | 将演示文稿的指定幻灯片保存为指定格式的文件。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的指定幻灯片保存为指定格式的文件。 |
| [`save(self, stream, slides, format)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 将演示文稿的指定幻灯片保存到指定格式的流中。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 将演示文稿的指定幻灯片保存到指定格式的流中。 |
| [`save(self, options)`](/slides/python-net/zh/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | 将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。 |
| [`get_images(self, options)`](/slides/python-net/zh/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | 返回演示文稿所有幻灯片的缩略图 Image 对象。 |
| [`get_images(self, options, slides)`](/slides/python-net/zh/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | 返回演示文稿指定幻灯片的缩略图 Bitmap 对象。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | 返回演示文稿所有幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | 返回演示文稿指定幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [`get_images(self, options, image_size)`](/slides/python-net/zh/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 返回演示文稿所有幻灯片的缩略图 Image 对象，使用指定尺寸。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/zh/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 返回演示文稿指定幻灯片的缩略图 Image 对象，使用指定尺寸。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/zh/aspose.slides/ipresentation/get_slide_by_id/#int) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | 在所有幻灯片的所有可接受形状的所有段落中合并具有相同格式的运行。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 将所有指定文本的出现替换为另一个指定文本。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh/aspose.slides/ipresentation/replace_regex/#str-str) | 将正则表达式的所有匹配项替换为指定字符串。 |

### 参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)