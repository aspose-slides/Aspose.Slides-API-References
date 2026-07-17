---
title: SwfOptions
second_title: Aspose.Slides for C++ API 参考
description: 提供用于控制演示文稿以 Swf 格式保存方式的选项。
type: docs
weight: 742
url: /zh/aspose.slides.export/swfoptions/
---
## SwfOptions 类

Provides options that control how a presentation is saved in Swf format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_Compressed](./get_compressed/)() override | 指定生成的 SWF 文档是否应压缩。默认是 **true**。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | 启用/禁用上下文菜单。默认是 true。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | 指定 JPEG 图像的质量。默认是 95。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | 将在查看器右上角显示为徽标的图像。图像应为 32x64 像素的 PNG 图像，否则徽标可能显示不正确。 |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | 获取徽标的完整超链接地址。仅在指定了 [set_LogoImageBytes()](./set_logoimagebytes/) 时有效。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示用于保存进度更新（百分比）的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | 显示/隐藏底部窗格。可以在 flashvars 中覆盖。默认是 true。 |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | 显示/隐藏全屏按钮。可以在 flashvars 中覆盖。默认是 true。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 指定生成的文档是否应包含隐藏的幻灯片。默认是 **false**。 |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | 显示/隐藏左侧窗格。可以在 flashvars 中覆盖。默认是 true。 |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | 指定是否显示页面周围的边框。默认是 true。 |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | 显示/隐藏页面步进器。可以在 flashvars 中覆盖。默认是 true。 |
| **bool** [get_ShowSearch](./get_showsearch/)() override | 显示/隐藏搜索区域。可以在 flashvars 中覆盖。默认是 true。 |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | 显示/隐藏整个顶部窗格。可以在 flashvars 中覆盖。默认是 true。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。读取 **bool**。默认值是 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 获取在导出演示文稿 [ISlidesLayoutOptions](../islideslayoutoptions/) 时幻灯片在页面上的布局模式。此属性不支持分配类型为 [HandoutLayoutingOptions](../handoutlayoutingoptions/) 的对象 |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | 以打开的左侧窗格开始。可以在 flashvars 中覆盖。默认是 false。 |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | 指定生成的 SWF 文档是否应包含集成的文档查看器。默认是 **true**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | 指定生成的 SWF 文档是否应压缩。默认是 **true**。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | 启用/禁用上下文菜单。默认是 true。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | 指定 JPEG 图像的质量。默认是 95。 |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | 将在查看器右上角显示为徽标的图像。图像应为 32x64 像素的 PNG 图像，否则徽标可能显示不正确。 |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | 设置徽标的完整超链接地址。仅在指定了 [set_LogoImageBytes()](./set_logoimagebytes/) 时有效。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用于保存进度更新（百分比）的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | 显示/隐藏底部窗格。可以在 flashvars 中覆盖。默认是 true。 |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | 显示/隐藏全屏按钮。可以在 flashvars 中覆盖。默认是 true。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 指定生成的文档是否应包含隐藏的幻灯片。默认是 **false**。 |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | 显示/隐藏左侧窗格。可以在 flashvars 中覆盖。默认是 true。 |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | 指定是否显示页面周围的边框。默认是 true。 |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | 显示/隐藏页面步进器。可以在 flashvars 中覆盖。默认是 true。 |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | 显示/隐藏搜索区域。可以在 flashvars 中覆盖。默认是 true。 |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | 显示/隐藏整个顶部窗格。可以在 flashvars 中覆盖。默认是 true。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。写入 **bool**。默认值是 **false**。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 设置在导出演示文稿 [ISlidesLayoutOptions](../islideslayoutoptions/) 时幻灯片在页面上的布局模式。此属性不支持分配类型为 [HandoutLayoutingOptions](../handoutlayoutingoptions/) 的对象 |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | 以打开的左侧窗格开始。可以在 flashvars 中覆盖。默认是 false。 |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | 指定生成的 SWF 文档是否应包含集成的文档查看器。默认是 **true**。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或设置接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [SwfOptions](./swfoptions/)() | 默认构造函数。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

The following example shows how to convert PowerPoint to SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## 另见

* 类 [SaveOptions](../saveoptions/)
* 类 [ISwfOptions](../iswfoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)