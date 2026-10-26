---
title: SVGOptions
second_title: Aspose.Slides for C++ API 参考
description: 表示 SVG 选项。
type: docs
weight: 703
url: /zh/aspose.slides.export/svgoptions/
---
## SVGOptions 类

表示 SVG 选项。

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | 返回默认设置。只读 [SVGOptions](./)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | 一个布尔标志，指示裁剪的部分是否保留在文档中。如果为 true，裁剪的部分将被移除；如果为 false，它们将被序列化到文档中（可能导致文件更大）。 |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | 确定 SVG 中是否禁用 3D 文本。读取 **bool**。 |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | 获取一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 **false**。 |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | 禁用 FromCornerX 和 FromCenter 渐变的拆分。读取 **bool**。 |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 缺乏为标记定义插入的能力。[Aspose.Slides](../../aspose.slides/) SVG 写入引擎对此问题有解决方案：它裁剪带箭头的线段末端，使线段不与标记重叠。此选项关闭此行为。读取 **bool**。 |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | 确定外部加载字体的处理方式。读取 [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回渐变的可视样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 提供控制导出文档中 [Ink](../../aspose.slides.ink/) 对象外观的选项。只读 [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | 确定 JPEG 编码质量。读取 **int32_t**。 |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | 返回元文件光栅化的最低分辨率限制。读取 **int32_t**。 |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | 表示图片压缩级别 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | 返回并设置一个回调接口，允许用户控制形状转换。读取 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | 返回用于生成最简最小 SVG 文件的设置。只读 [SVGOptions](./)。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | 确定在渲染时是否执行指定的形状旋转。读取 **bool**。默认值为 true。 |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | 确定文本框是否会包含在渲染区域中。读取 **bool**。默认值为 false。 |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | 确定幻灯片上的文本是否保存为图形。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | 返回用于生成最精确 SVG 文件的设置。只读 [SVGOptions](./)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | 一个布尔标志，指示裁剪的部分是否保留在文档中。如果为 true，裁剪的部分将被移除；如果为 false，它们将被序列化到文档中（可能导致文件更大）。 |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | 确定 SVG 中是否禁用 3D 文本。写入 **bool**。 |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | 设置一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 **false**。 |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | 禁用 FromCornerX 和 FromCenter 渐变的拆分。写入 **bool**。 |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 缺乏为标记定义插入的能力。[Aspose.Slides](../../aspose.slides/) SVG 写入引擎对此问题有解决方案：它裁剪带箭头的线段末端，使线段不与标记重叠。此选项关闭此行为。写入 **bool**。 |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | 确定外部加载字体的处理方式。写入 [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 设置渐变的可视样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | 确定 JPEG 编码质量。写入 **int32_t**。 |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | 设置元文件光栅化的最低分辨率限制。写入 **int32_t**。 |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | 表示图片压缩级别 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | 返回并设置一个回调接口，允许用户控制形状转换。写入 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | 确定在渲染时是否执行指定的形状旋转。写入 **bool**。默认值为 true。 |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | 确定文本框是否会包含在渲染区域中。写入 **bool**。默认值为 false。 |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | 确定幻灯片上的文本是否保存为图形。写入 **bool**。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；应使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；应使用智能指针或 ThisProtector。 |
|  [SVGOptions](./svgoptions/)() | 初始化 [SVGOptions](./) 类的新实例。 |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | 初始化 [SVGOptions](./) 类的新实例，指定链接嵌入控制器对象。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；应使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；应使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [SaveOptions](../saveoptions/)
* 类 [ISVGOptions](../isvgoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)