---
title: XamlOptions
second_title: Aspose.Slides C++ API 参考
description: 控制 XAML 文档保存方式的选项。
type: docs
weight: 27
url: /zh/aspose.slides.export.xaml/xamloptions/
---
## XamlOptions 类

控制 XAML 文档保存方式的选项。

```cpp
class XamlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::Xaml::IXamlOptions
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../../aspose.slides.export/saveoptions/get_defaultregularfont/)() override | 在未找到源字体时返回使用的字体。读取 [System::String](../../system/string/)。 |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | 确定是否导出隐藏的幻灯片。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../../aspose.slides.export/saveoptions/get_gradientstyle/)() override | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\> [get_OutputSaver](./get_outputsaver/)() override | 表示 IOutputSaver 接口的实现。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../../aspose.slides.export/saveoptions/get_progresscallback/)() override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/get_skipjavascriptlinks/)() override | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../../aspose.slides.export/saveoptions/get_warningcallback/)() override | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上并不复制任何内容，仅初始化新对象并允许对派生类进行复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，仅初始化新对象并允许对派生类进行复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
|  [SaveOptions](../../aspose.slides.export/saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../../aspose.slides.export/saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 在未找到源字体时设置使用的字体。写入 [System::String](../../system/string/)。 |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | 确定是否导出隐藏的幻灯片。 |
| void [set_GradientStyle](../../aspose.slides.export/saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_OutputSaver](./set_outputsaver/)([System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\>) override | 表示 IOutputSaver 接口的实现。 |
| void [set_ProgressCallback](../../aspose.slides.export/saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。 |
| void [set_WarningCallback](../../aspose.slides.export/saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [XamlOptions](./xamloptions/)() | 创建 [XamlOptions](./) 实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## 另见

* 类 [SaveOptions](../../aspose.slides.export/saveoptions/)
* 类 [IXamlOptions](../ixamloptions/)
* 命名空间 [Aspose::Slides::Export::Xaml](../)
* 库 [Aspose.Slides](../../)