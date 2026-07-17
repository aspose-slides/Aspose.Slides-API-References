---
title: MarkdownSaveOptions
second_title: Aspose.Slides C++ API 参考
description: 表示控制演示文稿如何保存为 markdown 的选项。
type: docs
weight: 547
url: /zh/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions 类

Represents options that control how presentation should be saved to markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | 指定保存包含资源的文档的基础路径。默认是应用程序的当前目录。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 返回在未找到源字体时使用的字体。读取 [System::String](../../system/string/)。 |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | 指定用于转换演示文稿的 markdown 规范。默认是 **TextOnly**。 |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | 指定用于转换演示文稿的 markdown 规范。默认是 **Multi-markdown**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回渐变的视觉样式。读取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | 指定在 Markdown 导出期间如何处理重复的常规空格字符。 |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | 指定用于保存图像的文件夹名称。默认是 **[Images](../../aspose.slides/images/)**。 |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | 指定生成的文档应使用的换行符：\r（Macintosh）、\n（Unix）或\r\n（Windows）。默认是 **Unix**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | 如果设置为 **true**，则从最终的 Markdown 输出中移除空行或仅包含空白的行。默认是 **false**。 |
| **bool** [get_ShowComments](./get_showcomments/)() const | 指定生成的文档是否显示注释。默认是 **false**。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | 指定生成的文档是否包含隐藏幻灯片。默认是 **false**。 |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | 指定生成的文档是否显示每张幻灯片的编号。默认是 **false**。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。读取 **bool**。默认值是 **false**。 |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | 获取在 Markdown 输出中用于幻灯片编号标题的格式字符串。格式必须包含 \"{0}\" 占位符，在导出时将被幻灯片索引替换。例如：\"# Slide {0}\" 将生成 \"# Slide 1\"、\"# Slide 2\" 等。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。读取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | 构造函数。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | 指定保存包含资源的文档的基础路径。默认是应用程序的当前目录。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的字体。写入 [System::String](../../system/string/)。 |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | 指定用于转换演示文稿的 markdown 规范。默认是 **TextOnly**。 |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | 指定用于转换演示文稿的 markdown 规范。默认是 **Multi-markdown**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 设置渐变的视觉样式。写入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | 指定在 Markdown 导出期间如何处理重复的常规空格字符。 |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | 指定用于保存图像的文件夹名称。默认是 **[Images](../../aspose.slides/images/)**。 |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | 指定生成的文档应使用的换行符：\r（Macintosh）、\n（Unix）或\r\n（Windows）。默认是 **Unix**。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用于以百分比保存进度更新的回调对象。参见 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | 如果设置为 **true**，则从最终的 Markdown 输出中移除空行或仅包含空白的行。默认是 **false**。 |
| void [set_ShowComments](./set_showcomments/)(**bool**) | 指定生成的文档是否显示注释。默认是 **false**。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定生成的文档是否包含隐藏幻灯片。默认是 **false**。 |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | 指定生成的文档是否显示每张幻灯片的编号。默认是 **false**。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。写入 **bool**。默认值是 **false**。 |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | 设置在 Markdown 输出中用于幻灯片编号标题的格式字符串。格式必须包含 \"{0}\" 占位符，在导出时将被幻灯片索引替换。例如：\"# Slide {0}\" 将生成 \"# Slide 1\"、\"# Slide 2\" 等。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。写入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应该直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应该直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应该直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应该直接调用；请改用智能指针或 ThisProtector。 |
| virtual [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | 在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）调用。<br>返回 **true** 以使用指定的 *link*，<br>或 **false** 以应用默认的保存逻辑。 |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | 在 Markdown 导出期间，对每个 SVG 图像调用。<br>返回 **true** 以使用指定的 *link*，<br>或 **false** 以应用默认的保存逻辑。 |

## 备注

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## 另见

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)