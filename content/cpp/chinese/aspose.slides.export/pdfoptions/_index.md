---
title: PdfOptions
second_title: Aspose.Slides C++ API 参考
description: 提供控制演示文稿以 Pdf 格式保存方式的选项。
type: docs
weight: 573
url: /zh/aspose.slides.export/pdfoptions/
---
## PdfOptions 类

提供控制演示文稿以 Pdf 格式保存方式的选项。

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | 包含一组标志，指定在以用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | 返回用户自定义的字体族名称数组，[Aspose.Slides](../../aspose.slides/) 应视为常用。阅读 [System::String](../../system/string/)[]。 |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | 如果为 **true**，则将指定的透明颜色应用于图像。 |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | 指示是否应为每个图像自动选择最有效的压缩（而非默认压缩）。如果设置为 **bool**.true，则对演示文稿中的每个图像将选择最合适的压缩算法，从而使生成的 PDF 文档更小。 |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | 生成的 PDF 文档所需的合规级别。读取 [PdfCompliance](../pdfcompliance/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | 如果为真，则在每张幻灯片周围绘制黑色框架。读取 **bool**。 |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | 确定是否应嵌入字体的所有字符或仅使用子集。读取 **bool**。 |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | 确定 [Aspose.Slides](../../aspose.slides/) 是否会为 ASCII（33..127 码范围）文本嵌入常用字体。对于大于 127 的字符码，[Fonts](../../aspose.slides/fonts/) 总是嵌入。常用字体列表包括 PDF 的基本 14 种字体和用户指定的附加字体。读取 **bool**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | 获取图像的透明颜色。 |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | 如果为真，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 提供控制导出文档中 [Ink](../../aspose.slides.ink/) 对象外观的选项。只读 [IInkOptions](../iinkoptions/)。 |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | 返回确定 PDF 文档中 JPEG 图像质量的值。读取 **uint8_t**。 |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | 设置用户密码以保护 PDF 文档。读取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | 指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存到 PDF。此方法可提升某些字体在生成的 PDF 中的文本质量。读取 **bool**。 |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | 如果为真，则将演示文稿中使用的所有元文件转换为 PNG 图像。读取 **bool**。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 指定生成的文档是否应包括隐藏的幻灯片。默认是 **false**。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 获取导出演示文稿 [ISlidesLayoutOptions](../islideslayoutoptions/) 时幻灯片在页面上放置的模式。 |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | 返回确定 PDF 文档中图像分辨率的值。 |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | 指定文档中所有文本内容使用的压缩类型。读取 [PdfTextCompression](../pdftextcompression/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或设置接收警告并决定加载过程是继续还是中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许对子类进行拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许对子类进行拷贝构造。 |
|  [PdfOptions](./pdfoptions/)() | 默认构造函数。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值降低共享引用计数。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | 包含一组标志，指定在以用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | 设置用户定义的字体族名称数组，[Aspose.Slides](../../aspose.slides/) 应视为常用。写入 [System::String](../../system/string/)[]。 |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | 如果为 **true**，则将指定的透明颜色应用于图像。 |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | 指示是否应为每个图像自动选择最有效的压缩（而非默认压缩）。如果设置为 **bool**.true，则对演示文稿中的每个图像将选择最合适的压缩算法，从而使生成的 PDF 文档更小。 |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | 生成的 PDF 文档所需的合规级别。写入 [PdfCompliance](../pdfcompliance/)。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | 如果为真，则在每张幻灯片周围绘制黑色框架。写入 **bool**。 |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | 确定是否应嵌入字体的所有字符或仅使用子集。写入 **bool**。 |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | 确定 [Aspose.Slides](../../aspose.slides/) 是否会为 ASCII（33..127 码范围）文本嵌入常用字体。[Fonts](../../aspose.slides/fonts/) 对于大于 127 的字符码总是嵌入。常用字体列表包括 PDF 的基本 14 种字体和用户指定的附加字体。写入 **bool**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | 设置图像的透明颜色。 |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | 如果为真，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。写入 **bool**。 |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | 设置确定 PDF 文档中 JPEG 图像质量的值。写入 **uint8_t**。 |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | 设置用户密码以保护 PDF 文档。写入 [System::String](../../system/string/)。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | 指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存到 PDF。此方法可提升某些字体在生成的 PDF 中的文本质量。写入 **bool**。 |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | 如果为真，则将演示文稿中使用的所有元文件转换为 PNG 图像。写入 **bool**。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 指定生成的文档是否应包括隐藏的幻灯片。默认是 **false**。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 设置导出演示文稿 [ISlidesLayoutOptions](../islideslayoutoptions/) 时幻灯片在页面上放置的模式。 |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | 设置确定 PDF 文档中图像分辨率的值。 |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | 指定文档中所有文本内容使用的压缩类型。写入 [PdfTextCompression](../pdftextcompression/)。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或设置接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注





以下示例展示了如何使用自定义选项将 PowerPoint 转换为 PDF。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// 实例化 PdfOptions 类
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// 设置 JPEG 质量
pdfOptions->set_JpegQuality(90);
// 设置元文件的行为
pdfOptions->set_SaveMetafilesAsPng(true);
// 设置文本压缩级别
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// 定义 PDF 标准
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// 将演示文稿保存为 PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
以下示例展示了如何将 PowerPoint 转换为带有隐藏幻灯片的 PDF。 
```cpp
// 实例化一个表示 PowerPoint 文件的 Presentation 类
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// 实例化 PdfOptions 类
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// 添加隐藏幻灯片
pdfOptions->set_ShowHiddenSlides(true);
// 将演示文稿保存为 PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
以下示例展示了如何将 PowerPoint 转换为受密码保护的 PDF。 
```cpp
// 实例化一个表示 PowerPoint 文件的 Presentation 对象
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// 设置 PDF 密码和访问权限
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// 将演示文稿保存为 PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
以下示例展示了如何将 PowerPoint 转换为带有备注的 PDF。 
```cpp
// 实例化一个表示演示文件的 Presentation 对象
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// 设置幻灯片类型和大小
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## 另见

* 类 [SaveOptions](../saveoptions/)
* 类 [IPdfOptions](../ipdfoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)