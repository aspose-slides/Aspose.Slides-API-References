---
title: ITiffOptions
second_title: Aspose.Slides for C++ API 参考
description: 提供控制演示文稿以 TIFF 格式保存方式的选项。
type: docs
weight: 495
url: /zh/aspose.slides.export/itiffoptions/
---
## ITiffOptions 类

Provides options that control how a presentation is saved in TIFF format.

```cpp
class ITiffOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() | 指定将彩色图像转换为黑白图像的算法。仅当 [ITiffOptions::get_CompressionType()](./get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 时才会应用此选项，读取 [BlackWhiteConversionMode](../blackwhiteconversionmode/)。默认值为 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)。 |
| virtual [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() | 指定压缩类型。读取 [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_DpiX](./get_dpix/)() | 指定水平分辨率（每英寸点数）。读取 **uint32_t**。 |
| virtual **uint32_t** [get_DpiY](./get_dpiy/)() | 指定垂直分辨率（每英寸点数）。读取 **uint32_t**。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() | 指定生成的 TIFF 图像的大小。默认值为 0x0，这意味着生成的图像大小将依据演示文稿幻灯片尺寸计算。读取 [System::Drawing::Size](../../system.drawing/size/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | 提供控制导出文档中 [Ink](../../aspose.slides.ink/) 对象外观的选项。只读 [IInkOptions](../iinkoptions/) |
| virtual [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() | 指定生成图像的像素格式。读取 [ImagePixelFormat](../imagepixelformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 指定生成的文档是否应包含隐藏幻灯片。默认值为 **false**。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 获取在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 返回接收警告并决定加载过程是继续还是中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 'is' 操作符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用将值类型对象与 nullptr 进行比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) | 指定将彩色图像转换为黑白图像的算法。仅当 [ITiffOptions::get_CompressionType()](./get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 时才会应用此选项，写入 [BlackWhiteConversionMode](../blackwhiteconversionmode/)。默认值为 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)。 |
| virtual void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) | 指定压缩类型。写入 [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_DpiX](./set_dpix/)(**uint32_t**) | 指定水平分辨率（每英寸点数）。写入 **uint32_t**。 |
| virtual void [set_DpiY](./set_dpiy/)(**uint32_t**) | 指定垂直分辨率（每英寸点数）。写入 **uint32_t**。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) | 指定生成的 TIFF 图像的大小。默认值为 0x0，这意味着生成的图像大小将依据演示文稿幻灯片尺寸计算。写入 [System::Drawing::Size](../../system.drawing/size/)。 |
| virtual void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) | 指定生成图像的像素格式。写入 [ImagePixelFormat](../imagepixelformat/)。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定生成的文档是否应包含隐藏幻灯片。默认值为 **false**。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 设置接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [ISaveOptions](../isaveoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)