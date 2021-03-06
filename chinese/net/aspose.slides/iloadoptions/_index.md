---
title: ILoadOptions
second_title: Aspose.Slides for .NET API 参考
description: 允许在加载演示文稿时指定其他选项例如格式或默认字体
type: docs
weight: 5780
url: /zh/net/aspose.slides/iloadoptions/
---
## ILoadOptions interface

允许在加载演示文稿时指定其他选项（例如格式或默认字体）。

```csharp
public interface ILoadOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | 表示可用于管理二进制大对象 (BLOB) 处理行为的选项， 例如使用临时文件或内存中的最大 BLOB 字节。这些选项旨在为特定环境或要求设置 最佳性能/内存消耗比。 二进制大对象 (BLOB) 是存储为单个实体的二进制数据 - 即 BLOB 可以 是音频、视频或演示文稿本身。 |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | 返回或设置在找不到源字体时使用的亚洲字体。 读写String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | 返回或设置在找不到源字体的情况下使用的常规字体。 读写String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | 返回或设置在找不到源字体时使用的符号字体。 读写String. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | 指定演示文稿要使用的外部字体的来源。 这些字体在演示文稿的整个生命周期内都可用，并且不与其他演示文稿共享 |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | 监视中断请求的令牌。  这个令牌管理整个[`IPresentation`](../ipresentation)实例生命周期。任何长时间运行的操作，例如presentaion 加载或保存，都将通过调用[`Interrupt`](../iinterruptiontokensource/interrupt) 的方法[`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | 返回或设置要加载的演示文稿的格式。 读/写[`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | 如果演示文件受密码保护，则此属性有意义。 值为 true 表示必须从加密的 演示文件中加载文档属性，并且必须忽略密码。 值为 false 表示必须加载整个加密演示文稿使用正确的 密码。 如果演示文稿未加密，则始终忽略属性值。 如果加密文件的文档属性不是公共的且属性值为true，则 无法加载文档属性并将引发异常。 读写Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | 获取或设置密码。 读写String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | 返回或设置管理外部资源加载的回调接口。 读/写[`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | 表示可用于指定其他电子表格行为的选项。 |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | 返回或设置一个对象，该对象接收警告并决定加载 进程是继续还是中止。 读/写[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### 也可以看看

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
