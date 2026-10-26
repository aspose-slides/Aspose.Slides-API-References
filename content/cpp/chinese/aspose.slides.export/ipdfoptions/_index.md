---
title: IPdfOptions
second_title: Aspose.Slides for C++ API 参考
description: 提供控制演示文稿以 Pdf 格式保存的选项。
type: docs
weight: 274
url: /zh/aspose.slides.export/ipdfoptions/
---
## IPdfOptions 类


提供控制演示文稿以 Pdf 格式保存的方式的选项。

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | 返回用户自定义的字体族名称数组，[Aspose.Slides](../../aspose.slides/) 应视为通用。阅读 [System::String](../../system/string/)[]。 |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | 如果为 **true**，则将指定的透明颜色应用于图像。 |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | 指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 **bool**.true，则演示文稿中的每个图像都会选择最合适的压缩算法，从而导致生成的 PDF 文档体积更小。 |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | 生成的 PDF 文档的所需符合级别。阅读 [PdfCompliance](../pdfcompliance/)。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | 如果为真，则在每个幻灯片周围绘制黑色框架。阅读 **bool**。 |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | 确定是否应嵌入字体的所有字符或仅使用子集。阅读 **bool**。 |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | 如果为真，则为 ASCII 字符 32-127 嵌入 TrueType 字体。[Fonts](../../aspose.slides/fonts/) 对于字符代码大于 127 的始终嵌入。阅读 **bool**。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 返回渐变的视觉样式。阅读 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | 获取图像的透明颜色。 |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | 如果为 **true**，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。阅读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | 提供控制导出文档中 [Ink](../../aspose.slides.ink/) 对象外观的选项。只读 [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | 返回决定 PDF 文档中 JPEG 图像质量的值。阅读 **uint8_t**。 |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | 设置用户密码以保护 PDF 文档。阅读 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | 指示当字体不支持粗体样式时，是否应将文本光栅化为位图并保存到 PDF。此方法可以提升某些字体在生成的 PDF 中的文本质量。阅读 **bool**。 |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | 如果为真，则将演示文稿中使用的所有元文件转换为 PNG 图像。阅读 **bool**。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 指定生成的文档是否应包含隐藏的幻灯片。默认值为 **false**。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。阅读 **bool**。默认值为 **false**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 获取导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | 返回决定 PDF 文档中图像分辨率的值。 |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | 指定文档中所有文本内容使用的压缩类型。阅读 [PdfTextCompression](../pdftextcompression/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 返回接收警告并决定加载过程是继续还是中止的对象。阅读 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | 设置用户自定义的字体族名称数组，[Aspose.Slides](../../aspose.slides/) 应视为通用。写入 [System::String](../../system/string/)[]。 |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | 如果为 **true**，则将指定的透明颜色应用于图像。 |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | 指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 **bool**.true，则演示文稿中的每个图像都会选择最合适的压缩算法，从而导致生成的 PDF 文档体积更小。 |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | 生成的 PDF 文档的所需符合级别。写入 [PdfCompliance](../pdfcompliance/)。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | 如果为真，则在每个幻灯片周围绘制黑色框架。写入 **bool**。 |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | 确定是否应嵌入字体的所有字符或仅使用子集。写入 **bool**。 |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | 如果为真，则为 ASCII 字符 32-127 嵌入 TrueType 字体。[Fonts](../../aspose.slides/fonts/) 对于字符代码大于 127 的始终嵌入。写入 **bool**。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | 设置图像的透明颜色。 |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | 如果为 **true**，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。写入 **bool**。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | 设置决定 PDF 文档中 JPEG 图像质量的值。写入 **uint8_t**。 |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | 设置用户密码以保护 PDF 文档。写入 [System::String](../../system/string/)。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | 指示当字体不支持粗体样式时，是否应将文本光栅化为位图并保存到 PDF。此方法可以提升某些字体在生成的 PDF 中的文本质量。写入 **bool**。 |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | 如果为真，则将演示文稿中使用的所有元文件转换为 PNG 图像。写入 **bool**。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定生成的文档是否应包含隐藏的幻灯片。默认值为 **false**。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 设置导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | 设置决定 PDF 文档中图像分辨率的值。 |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | 指定文档中所有文本内容使用的压缩类型。写入 [PdfTextCompression](../pdftextcompression/)。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 设置接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [ISaveOptions](../isaveoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)