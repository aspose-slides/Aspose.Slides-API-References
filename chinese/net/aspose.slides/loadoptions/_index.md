---
title: LoadOptions
second_title: Aspose.Slides for .NET API 参考
description: 允许在加载演示文稿时指定其他选项例如格式或默认字体
type: docs
weight: 7140
url: /zh/net/aspose.slides/loadoptions/
---
## LoadOptions class

允许在加载演示文稿时指定其他选项（例如格式或默认字体）。

```csharp
public class LoadOptions : ILoadOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | 创建新的默认加载选项。 |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | 创建新的加载选项。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | 表示可用于管理二进制大对象 (BLOB) 处理行为的选项， 例如使用临时文件或最大 BLOB 字节在记忆中。这些选项旨在为特定环境或要求设置 最佳性能/内存消耗比。  二进制大对象 (BLOB) 是存储为单个实体的二进制数据 - 即 BLOB 可以 是音频、视频或演示文稿本身. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | 返回或设置在找不到源字体时使用的亚洲字体。 读/写String。 |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | 返回或设置在未找到源字体时使用的常规字体。 读/写String。 |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | 返回或设置在找不到源字体时使用的符号字体。 读/写String。 |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | 指定演示文稿使用的外部字体的来源。 这些字体在演示文稿的整个生命周期内都可以使用，并且不与其他演示文稿共享 |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | 监视中断请求的令牌。  此令牌管理整个[`IPresentation`](../ipresentation)实例生命周期。任何长时间运行的操作，例如加载 或保存演示文稿，都将通过调用[`Interrupt`](../interruptiontokensource/interrupt)方法中断 [`InterruptionTokenSource`](../interruptiontokensource)。 |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | 返回或设置要加载的演示文稿的格式。 读/写[`LoadFormat`](../loadformat)。 |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | 如果演示文件受密码保护，此属性是有意义的。 值为 true 意味着只有文档属性必须从加密的 演示文件中加载，并且必须忽略密码。 false 值意味着必须使用正确的 密码加载整个加密的演示文稿。 如果演示文稿未加密，则始终忽略属性值。 如果加密文件的文档属性不是公开的且属性值为 true，则 文档属性无法加载，将引发异常。 读/写Boolean。 |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | 获取或设置密码。 读/写String。 |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | 返回或设置管理外部资源加载的回调接口。 读/写[`IResourceLoadingCallback`](../iresourceloadingcallback)。 |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | 获取电子表格的选项。例如，这些选项会影响图表的计算公式。 |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | 返回或设置一个对象，该对象接收警告并决定加载 过程是继续还是中止。 读/写[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 也可以看看

* interface [ILoadOptions](../iloadoptions)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->