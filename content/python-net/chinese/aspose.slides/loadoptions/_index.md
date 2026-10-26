---
title: LoadOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/loadoptions/
---
## LoadOptions 类

允许在加载演示文稿时指定附加选项（例如格式或默认字体）。

LoadOptions 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/loadoptions/__init__/#) | 创建新的默认加载选项。 |
| [`__init__(self, load_format)`](/slides/python-net/zh/aspose.slides/loadoptions/__init__/#loadformat) | 创建新的加载选项。 |

## 属性

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/zh/aspose.slides/loadoptions/load_format/) | 返回或设置要加载的演示文稿的格式。<br/>            读取/写入 [`LoadFormat`](/slides/python-net/zh/aspose.slides/loadformat)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides/loadoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的常规字体。<br/>            读取/写入 **str**。 |
| [`default_symbol_font`](/slides/python-net/zh/aspose.slides/loadoptions/default_symbol_font/) | 返回或设置在未找到源字体时使用的符号字体。<br/>            读取/写入 **str**。 |
| [`default_asian_font`](/slides/python-net/zh/aspose.slides/loadoptions/default_asian_font/) | 返回或设置在未找到源字体时使用的亚洲字体。<br/>            读取/写入 **str**。 |
| [`password`](/slides/python-net/zh/aspose.slides/loadoptions/password/) | 获取或设置密码。<br/>            读取/写入 **str**。 |
| [`only_load_document_properties`](/slides/python-net/zh/aspose.slides/loadoptions/only_load_document_properties/) | 如果演示文稿文件受密码保护，则此属性有意义。<br/>            true 值表示只能从加密的演示文稿文件中加载文档属性，并且必须忽略密码。<br/>            false 值表示必须使用正确的密码加载整个加密的演示文稿。<br/>            如果演示文稿未加密，则始终忽略属性值。<br/>            如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并会抛出异常。<br/>            读取/写入 **bool**。 |
| [`warning_callback`](/slides/python-net/zh/aspose.slides/loadoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。<br/>            读取/写入 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`blob_management_options`](/slides/python-net/zh/aspose.slides/loadoptions/blob_management_options/) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，<br/>            如使用临时文件或内存中最大 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比例。<br/>            二进制大对象（BLOB）是一种作为单一实体存储的二进制数据 —— 即 BLOB 可以是音频、视频或演示文稿本身。 |
| [`document_level_font_sources`](/slides/python-net/zh/aspose.slides/loadoptions/document_level_font_sources/) | 指定演示文稿使用的外部字体来源。<br/>            这些字体在演示文稿的整个生命周期内可用，并且不与其他演示文稿共享。 |
| [`interruption_token`](/slides/python-net/zh/aspose.slides/loadoptions/interruption_token/) | 用于监视中断请求的令牌。<br/>            <br/>            此令牌管理整个 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的生命周期。任何长时间运行的操作，例如加载<br/>            或保存演示文稿，都将在调用 [`InterruptionTokenSource`](/slides/python-net/zh/aspose.slides/interruptiontokensource) 的 [`InterruptionTokenSource.interrupt`](/slides/python-net/zh/aspose.slides/interruptiontokensource/interrupt) 方法时被中断。 |
| [`resource_loading_callback`](/slides/python-net/zh/aspose.slides/loadoptions/resource_loading_callback/) | 返回或设置管理外部资源加载的回调接口。<br/>            读取/写入 [`IResourceLoadingCallback`](/slides/python-net/zh/aspose.slides/iresourceloadingcallback)。 |
| [`spreadsheet_options`](/slides/python-net/zh/aspose.slides/loadoptions/spreadsheet_options/) | 获取电子表格的选项。例如，这些选项会影响图表公式的计算。 |
| [`default_text_language`](/slides/python-net/zh/aspose.slides/loadoptions/default_text_language/) | 返回或设置演示文稿文本的默认语言。<br/>            读取/写入 **str**。 |
| [`delete_embedded_binary_objects`](/slides/python-net/zh/aspose.slides/loadoptions/delete_embedded_binary_objects/) | 确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。<br/>            <br/>嵌入的二进制对象类型：<br/><br/><br/>* VBA 项目 [`IPresentation.vba_project`](/slides/python-net/zh/aspose.slides/ipresentation/vba_project)<br/>* OLE 对象嵌入数据 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX 控件二进制数据 [`IControl.active_x_control_binary`](/slides/python-net/zh/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            读取/写入 **bool**。 |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)