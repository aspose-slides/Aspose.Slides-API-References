---
title: TiffOptions
second_title: Aspose.Slides for C++ API 参考
description: 提供控制演示文稿以 TIFF 格式保存的选项。
type: docs
weight: 768
url: /zh/aspose.slides.export/tiffoptions/
---
## TiffOptions 类

提供控制演示文稿以 TIFF 格式保存的选项。

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 样式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 样式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | 指定将彩色图像转换为黑白图像的算法。仅当 [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 时此选项才会生效，读取 [BlackWhiteConversionMode](../blackwhiteconversionmode/)。默认值为 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)。 |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | 指定压缩类型。读取 [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| **uint32_t** [get_DpiX](./get_dpix/)() override | 指定水平分辨率（每英寸点数）。读取 **uint32_t**。 |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | 指定垂直分辨率（每英寸点数）。读取 **uint32_t**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | 指定生成的 TIFF 图像的大小。默认值为 0x0，这意味着生成的图像大小将根据演示文稿幻灯片尺寸计算。读取 [System::Drawing::Size](../../system.drawing/size/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 提供控制导出文档中 [Ink](../../aspose.slides.ink/) 对象外观的选项。只读 [IInkOptions](../iinkoptions/)。 |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | 指定生成图像的像素格式。读取 [ImagePixelFormat](../imagepixelformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示用于保存进度更新（百分比）的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 指定生成的文档是否应包含隐藏幻灯片。默认值为 **false**。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 获取导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | 指定将彩色图像转换为黑白图像的算法。仅当 [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 时此选项才会生效，写入 [BlackWhiteConversionMode](../blackwhiteconversionmode/)。默认值为 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)。 |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | 指定压缩类型。写入 [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | 指定水平分辨率（每英寸点数）。写入 **uint32_t**。 |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | 指定垂直分辨率（每英寸点数）。写入 **uint32_t**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | 指定生成的 TIFF 图像的大小。默认值为 0x0，这意味着生成的图像大小将根据演示文稿幻灯片尺寸计算。写入 [System::Drawing::Size](../../system.drawing/size/)。 |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | 指定生成图像的像素格式。写入 [ImagePixelFormat](../imagepixelformat/)。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用于保存进度更新（百分比）的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 指定生成的文档是否应包含隐藏幻灯片。默认值为 **false**。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [TiffOptions](./tiffoptions/)() | 默认构造函数。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

以下示例演示如何使用默认大小将 PowerPoint 转换为 TIFF。
```cpp
// 实例化一个表示演示文件的 Presentation 对象
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// 将演示文稿保存为 TIFF 文档
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
以下示例演示如何使用自定义大小将 PowerPoint 转换为 TIFF。
```cpp
// 实例化一个表示演示文件的 Presentation 对象
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// 实例化 TiffOptions 类
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// 设置压缩类型
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Compression Types
// Default - 指定默认压缩方案 (LZW)。
// None - 指定无压缩。
// CCITT3
// CCITT4
// LZW
// RLE
// 深度取决于压缩类型，不能手动设置。
// 分辨率单位始终等于 "2"（每英寸点数）
// 设置图像 DPI
opts->set_DpiX(200);
opts->set_DpiY(100);
// 设置图像大小
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// 将演示文稿保存为具有指定图像大小的 TIFF
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
以下示例演示如何使用自定义图像像素格式将 PowerPoint 转换为 TIFF。
```cpp
// 实例化一个表示演示文件的 Presentation 对象
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// 将演示文稿保存为具有指定图像大小的 TIFF
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## 另见

* 类 [SaveOptions](../saveoptions/)
* 类 [ITiffOptions](../itiffoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)