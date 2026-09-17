---
title: ILoadOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iloadoptions/
---
## ILoadOptions 类

允许在加载演示文稿时指定其他选项（例如格式或默认字体）。

ILoadOptions 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`load_format`](/slides/python-net/zh/aspose.slides/iloadoptions/load_format/) | 返回或设置要加载的演示文稿的格式。<br/>            读/写 [`LoadFormat`](/slides/python-net/zh/aspose.slides/loadformat)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides/iloadoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的常规字体。<br/>            读写 **str**。 |
| [`default_symbol_font`](/slides/python-net/zh/aspose.slides/iloadoptions/default_symbol_font/) | 返回或设置在未找到源字体时使用的符号字体。<br/>            读写 **str**。 |
| [`default_asian_font`](/slides/python-net/zh/aspose.slides/iloadoptions/default_asian_font/) | 返回或设置在未找到源字体时使用的亚洲字体。<br/>            读写 **str**。 |
| [`password`](/slides/python-net/zh/aspose.slides/iloadoptions/password/) | 获取或设置密码。<br/>            读写 **str**。 |
| [`only_load_document_properties`](/slides/python-net/zh/aspose.slides/iloadoptions/only_load_document_properties/) | 如果演示文稿文件受密码保护，则此属性有意义。<br/>            值为 true 表示只能从加密的演示文稿文件加载文档属性，并且忽略密码。<br/>            值为 false 表示必须使用正确的密码加载整个加密的演示文稿。<br/>            如果演示文稿未加密，则始终忽略属性值。<br/>            如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并抛出异常。<br/>            读写 **bool**。 |
| [`warning_callback`](/slides/python-net/zh/aspose.slides/iloadoptions/warning_callback/) | 返回或设置接收警告并决定加载<br/>            过程是继续还是中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`blob_management_options`](/slides/python-net/zh/aspose.slides/iloadoptions/blob_management_options/) | 表示可用于管理二进制大对象 (BLOB) 处理行为的选项，<br/>            如使用临时文件或在内存中限制 BLOB 的最大字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比例。<br/>            二进制大对象 (BLOB) 是作为单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示文稿本身。 |
| [`document_level_font_sources`](/slides/python-net/zh/aspose.slides/iloadoptions/document_level_font_sources/) | 指定演示文稿使用的外部字体来源。<br/>            这些字体在演示文稿的整个生命周期内可用，且不会与其他演示文稿共享 |
| [`interruption_token`](/slides/python-net/zh/aspose.slides/iloadoptions/interruption_token/) | 用于监视中断请求的令牌。<br/>            <br/>            此令牌管理整个 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的生命周期。任何长期运行的操作，例如演示文稿<br/>            加载或保存，都将通过调用 [`IInterruptionTokenSource.interrupt`](/slides/python-net/zh/aspose.slides/iinterruptiontokensource/interrupt) 方法来中断<br/>            [`IInterruptionTokenSource`](/slides/python-net/zh/aspose.slides/iinterruptiontokensource)。 |
| [`resource_loading_callback`](/slides/python-net/zh/aspose.slides/iloadoptions/resource_loading_callback/) | 返回或设置管理外部资源加载的回调接口。<br/>            读/写 [`IResourceLoadingCallback`](/slides/python-net/zh/aspose.slides/iresourceloadingcallback)。 |
| [`spreadsheet_options`](/slides/python-net/zh/aspose.slides/iloadoptions/spreadsheet_options/) | 表示可用于指定附加电子表格行为的选项。 |
| [`default_text_language`](/slides/python-net/zh/aspose.slides/iloadoptions/default_text_language/) | 返回或设置演示文稿文本的默认语言。<br/>            读/写 **str**。 |
| [`delete_embedded_binary_objects`](/slides/python-net/zh/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | 确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。<br/>            <br/>嵌入的二进制对象类型：<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/zh/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/zh/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            读/写 **bool**。 |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)