---
title: ISwfOptions
second_title: Aspose.Slides for C++ API 参考
description: 提供控制演示文稿以 SWF 格式保存方式的选项。
type: docs
weight: 469
url: /zh/aspose.slides.export/iswfoptions/
---
## ISwfOptions 类

提供控制演示文稿以 SWF 格式保存方式的选项。

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **bool** [get_Compressed](./get_compressed/)() | 指定生成的 SWF 文档是否应压缩。默认值为 **true**。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | 启用/禁用上下文菜单。默认值为 true。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 返回渐变的可视样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | 指定 JPEG 图像的质量。 \n\n 默认值为 95。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | 将在查看器右上角显示为徽标的图像。 \n\n 图像应为 32x64 像素的 PNG，，否则徽标可能显示不正确。 |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | 获取徽标的完整超链接地址。仅在指定了 [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) 时有效。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | 显示/隐藏底部窗格。可在 flashvars 中覆盖。默认值为 true。 |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | 显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 指定生成的文档是否应包含隐藏的幻灯片。默认值为 **false**。 |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | 显示/隐藏左侧窗格。可在 flashvars 中覆盖。默认值为 true。 |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | 指定是否显示页面周围的边框。默认值为 true。 |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | 显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true。 |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | 显示/隐藏搜索区域。可在 flashvars 中覆盖。默认值为 true。 |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | 显示/隐藏整个顶部窗格。可在 flashvars 中覆盖。默认值为 true。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 获取导出演示文稿 [ISlidesLayoutOptions](../islideslayoutoptions/) 时幻灯片在页面上的布局模式。此属性不支持分配类型为 **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 的对象。 |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | 默认左侧窗格打开。可在 flashvars 中覆盖。默认值为 false。 |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | 指定生成的 SWF 文档是否应包含集成的文档查看器。默认值为 **true**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 返回接收警告并决定加载过程是继续还是中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的散列。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许复制构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许复制构造子类。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | 指定生成的 SWF 文档是否应压缩。默认值为 **true**。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | 启用/禁用上下文菜单。默认值为 true。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 设置渐变的可视样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | 指定 JPEG 图像的质量。 \n\n 默认值为 95。 |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 将在查看器右上角显示为徽标的图像。 \n\n 图像应为 32x64 像素的 PNG， sonst 徽标可能显示不正确。 |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | 设置徽标的完整超链接地址。仅在指定了 [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) 时有效。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | 显示/隐藏底部窗格。可在 flashvars 中覆盖。默认值为 true。 |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | 显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定生成的文档是否应包含隐藏的幻灯片。默认值为 **false**。 |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | 显示/隐藏左侧窗格。可在 flashvars 中覆盖。默认值为 true。 |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | 指定是否显示页面周围的边框。默认值为 true。 |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | 显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true。 |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | 显示/隐藏搜索区域。可在 flashvars 中覆盖。默认值为 true。 |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | 显示/隐藏整个顶部窗格。可在 flashvars 中覆盖。默认值为 true。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 设置导出演示文稿 [ISlidesLayoutOptions](../islideslayoutoptions/) 时幻灯片在页面上的布局模式。此属性不支持分配类型为 **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 的对象。 |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | 默认左侧窗格打开。可在 flashvars 中覆盖。默认值为 false。 |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | 指定生成的 SWF 文档是否应包含集成的文档查看器。默认值为 **true**。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) * | 设置接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
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

## 另请参阅

* 类 [ISaveOptions](../isaveoptions/)
* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)