---
title: IDocumentProperties class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/idocumentproperties/
---
## IDocumentProperties 类

表示演示文稿的属性。

IDocumentProperties 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/zh/aspose.slides/idocumentproperties/app_version/) | 返回应用程序版本。<br/>            只读 **str**。 |
| [`name_of_application`](/slides/python-net/zh/aspose.slides/idocumentproperties/name_of_application/) | 返回或设置应用程序的名称。<br/>            读写 **str**。 |
| [`company`](/slides/python-net/zh/aspose.slides/idocumentproperties/company/) | 返回或设置公司属性。<br/>            读写 **str**。 |
| [`manager`](/slides/python-net/zh/aspose.slides/idocumentproperties/manager/) | 返回或设置管理员属性。<br/>            读写 **str**。 |
| [`presentation_format`](/slides/python-net/zh/aspose.slides/idocumentproperties/presentation_format/) | 返回或设置演示文稿的目标格式。<br/>            读写 **str**。 |
| [`shared_doc`](/slides/python-net/zh/aspose.slides/idocumentproperties/shared_doc/) | 确定演示文稿是否在多个人之间共享。<br/>            读写 **bool**。 |
| [`application_template`](/slides/python-net/zh/aspose.slides/idocumentproperties/application_template/) | 返回或设置应用程序的模板。<br/>            读写 **str**。 |
| [`total_editing_time`](/slides/python-net/zh/aspose.slides/idocumentproperties/total_editing_time/) | 演示文稿的总编辑时间。<br/>            读写 **System.TimeSpan**。 |
| [`title`](/slides/python-net/zh/aspose.slides/idocumentproperties/title/) | 返回或设置演示文稿的标题。<br/>            读写 **str**。 |
| [`subject`](/slides/python-net/zh/aspose.slides/idocumentproperties/subject/) | 返回或设置演示文稿的主题。<br/>            读写 **str**。 |
| [`author`](/slides/python-net/zh/aspose.slides/idocumentproperties/author/) | 返回或设置演示文稿的作者。<br/>            读写 **str**。 |
| [`keywords`](/slides/python-net/zh/aspose.slides/idocumentproperties/keywords/) | 返回或设置演示文稿的关键字。<br/>            读写 **str**。 |
| [`comments`](/slides/python-net/zh/aspose.slides/idocumentproperties/comments/) | 返回或设置演示文稿的注释。<br/>            读写 **str**。 |
| [`category`](/slides/python-net/zh/aspose.slides/idocumentproperties/category/) | 返回或设置演示文稿的类别。<br/>            读写 **str**。 |
| [`created_time`](/slides/python-net/zh/aspose.slides/idocumentproperties/created_time/) | 返回演示文稿的创建日期。<br/>            值采用 UTC。<br/>            读写 **System.DateTime**。 |
| [`last_saved_time`](/slides/python-net/zh/aspose.slides/idocumentproperties/last_saved_time/) | 返回演示文稿的最后修改日期。<br/>            值采用 UTC。<br/>            在 Presentation.DocumentProperties 情况下为只读（因为在保存 IPresentation 对象的过程中会内部更新）。<br/>            可通过方法 [`IPresentationInfo.read_document_properties`](/slides/python-net/zh/aspose.slides/ipresentationinfo/read_document_properties) 返回的 DocumentProperties 实例进行更改。<br/>            请参见 **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** 方法摘要中的示例。 |
| [`last_printed`](/slides/python-net/zh/aspose.slides/idocumentproperties/last_printed/) | 返回演示文稿上次打印的日期。<br/>            读写 **System.DateTime**。 |
| [`last_saved_by`](/slides/python-net/zh/aspose.slides/idocumentproperties/last_saved_by/) | 返回或设置最后修改演示文稿的人的名称。<br/>            读写 **str**。 |
| [`revision_number`](/slides/python-net/zh/aspose.slides/idocumentproperties/revision_number/) | 返回或设置演示文稿的修订号。<br/>            读写 **int**。 |
| [`content_status`](/slides/python-net/zh/aspose.slides/idocumentproperties/content_status/) | 返回或设置演示文稿的内容状态。<br/>            读写 **str**。 |
| [`content_type`](/slides/python-net/zh/aspose.slides/idocumentproperties/content_type/) | 返回或设置演示文稿的内容类型。<br/>            读写 **str**。 |
| [`hyperlink_base`](/slides/python-net/zh/aspose.slides/idocumentproperties/hyperlink_base/) | 返回或设置 HyperlinkBase 文档属性。<br/>            读写 **str**。 |
| [`scale_crop`](/slides/python-net/zh/aspose.slides/idocumentproperties/scale_crop/) | 指示文档缩略图的显示模式。<br/>            将此元素设为 **true** 以启用将文档缩略图缩放至显示区域。<br/>            将此元素设为 **false** 以启用裁剪文档缩略图，仅显示适合显示区域的部分。<br/>            读写 **bool**。 |
| [`links_up_to_date`](/slides/python-net/zh/aspose.slides/idocumentproperties/links_up_to_date/) | 指示文档中的超链接是否为最新。<br/>            将此元素设为 **true** 表示超链接已更新。<br/>            将此元素设为 **false** 表示超链接已过时。<br/>            读写 **bool**。 |
| [`hyperlinks_changed`](/slides/python-net/zh/aspose.slides/idocumentproperties/hyperlinks_changed/) | 指定此部分中的一个或多个超链接已由生产者专门在此部分更新。<br/>            下一个打开此文档的生产者应使用此部分中指定的新超链接更新超链接关系。<br/>            读写 **bool**。 |
| [`slides`](/slides/python-net/zh/aspose.slides/idocumentproperties/slides/) | 指定演示文稿文档中的幻灯片总数。<br/zh/>            只读 **int**。 |
| [`hidden_slides`](/slides/python-net/zh/aspose.slides/idocumentproperties/hidden_slides/) | 指定演示文稿文档中隐藏的幻灯片数量。<br/>            只读 **int**。 |
| [`notes`](/slides/python-net/zh/aspose.slides/idocumentproperties/notes/) | 指定演示文稿中包含备注的幻灯片数量。<br/>            只读 **int**。 |
| [`paragraphs`](/slides/python-net/zh/aspose.slides/idocumentproperties/paragraphs/) | 在适用的情况下，指定文档中找到的段落总数。<br/>            只读 **int**。 |
| [`words`](/slides/python-net/zh/aspose.slides/idocumentproperties/words/) | 指定文档中包含的单词总数。<br/>            只读 **int**。 |
| [`multimedia_clips`](/slides/python-net/zh/aspose.slides/idocumentproperties/multimedia_clips/) | 指定文档中存在的音频或视频剪辑的总数。<br/>            只读 **int**。 |
| [`titles_of_parts`](/slides/python-net/zh/aspose.slides/idocumentproperties/titles_of_parts/) | 指定每个文档部分的标题。<br/>            这些部分并非实际文档部分，而是文档章节的概念性表示。<br/>            只读 **List[str]**。 |
| [`heading_pairs`](/slides/python-net/zh/aspose.slides/idocumentproperties/heading_pairs/) | 指示文档部分的分组以及每组的部分数量。<br/>            只读 **List[IHeadingPair]**。 |
| [`count_of_custom_properties`](/slides/python-net/zh/aspose.slides/idocumentproperties/count_of_custom_properties/) | 返回集合中实际包含的自定义属性数量。<br/>            只读 **int**。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 从自定义属性获取指定名称的布尔值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 从自定义属性获取指定名称的整数值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 从自定义属性获取指定名称的 DateTime 值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 从自定义属性获取指定名称的字符串值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | 设置指定名称的布尔自定义属性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | 设置指定名称的整数自定义属性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | 设置指定名称的 DateTime 自定义属性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | 设置指定名称的字符串自定义属性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | 设置指定名称的 float 自定义属性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | 设置指定名称的 double 自定义属性。 |
| [`get_custom_property_name(self, index)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_custom_property_name/#int) | 返回指定索引处的自定义属性名称。 |
| [`remove_custom_property(self, name)`](/slides/python-net/zh/aspose.slides/idocumentproperties/remove_custom_property/#str) | 移除与指定名称关联的自定义属性。 |
| [`contains_custom_property(self, name)`](/slides/python-net/zh/aspose.slides/idocumentproperties/contains_custom_property/#str) | 检查是否存在具有指定名称的自定义属性。 |
| [`clear_custom_properties(self)`](/slides/python-net/zh/aspose.slides/idocumentproperties/clear_custom_properties/#) | 移除所有自定义属性。 |
| [`clear_built_in_properties(self)`](/slides/python-net/zh/aspose.slides/idocumentproperties/clear_built_in_properties/#) | 清除并为所有内置属性设置默认值。 |
| [`get_sensitivity_labels(self)`](/slides/python-net/zh/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | 从自定义文档属性获取敏感度标签数组（Microsoft Information Protection SDK 元数据）。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)