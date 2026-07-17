---
title: IRenderingOptions
second_title: Aspose.Slides for C++ API 参考
description: 提供用于控制演示文稿/幻灯片渲染方式的选项。
type: docs
weight: 326
url: /zh/aspose.slides.export/irenderingoptions/
---
## IRenderingOptions 类

Provides options that control how a presentation/slide is rendered.

```cpp
class IRenderingOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN 本身）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN 本身）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | 获取一个值，指示文本是否在不使用连字的情况下渲染。设置为 **true** 时，渲染输出中将禁用连字。默认情况下，此属性设置为 **false**。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | 提供用于控制导出文档中 [Ink](../../aspose.slides.ink/) 对象外观的选项。只读 [IInkOptions](../iinkoptions/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 获取导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 返回一个接收警告并决定加载过程是继续还是中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的专门化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的专门化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | 设置一个值，指示文本是否在不使用连字的情况下渲染。设置为 **true** 时，渲染输出中将禁用连字。默认情况下，此属性设置为 **false**。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 设置导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 设置一个接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
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
## 备注

```cpp
using System::Drawing::Imaging::ImageFormat;

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayoutingOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
notesCommentsLayoutingOptions->set_NotesPosition(NotesPositions::BottomTruncated);

System::SharedPtr<IRenderingOptions> renderingOpts = System::MakeObject<RenderingOptions>();
renderingOpts->set_SlidesLayoutOptions(notesCommentsLayoutingOptions);

System::Shared_Ptr<ISlide> slide = pres->get_Slide(0);

slide->GetThumbnail(renderingOpts)->Save(u"pres-Original.png", ImageFormat::get_Png());

renderingOpts->set_DefaultRegularFont(u"Arial Black");
slide->GetThumbnail(renderingOpts)->Save(u"pres-ArialBlackDefault.png", ImageFormat::get_Png());

renderingOpts->set_DefaultRegularFont(u"Arial Narrow");
slide->GetThumbnail(renderingOpts)->Save(u"pres-ArialNarrowDefault.png", ImageFormat::get_Png());
```

## 另见

* 类 [ISaveOptions](../isaveoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)