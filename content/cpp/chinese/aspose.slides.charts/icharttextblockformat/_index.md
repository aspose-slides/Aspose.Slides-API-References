---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API 参考
description: 表示图表文本元素的格式属性。
type: docs
weight: 885
url: /zh/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat 类

表示图表文本元素的格式属性。

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | 返回 [TextFrame](../../aspose.slides/textframe/) 中的垂直锚点文本。阅读 [TextAnchorType](../../aspose.slides/textanchortype/)。 |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | 返回文本的自动适配模式。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。阅读 [TextAutofitType](../../aspose.slides/textautofittype/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | 如果 [NullableBool::True](../../aspose.slides/nullablebool/)，则文本应在框中水平居中。阅读 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | 返回 [TextFrame](../../aspose.slides/textframe/) 中的底部边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。读取 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | 返回 [TextFrame](../../aspose.slides/textframe/) 中的左侧边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。读取 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | 返回 [TextFrame](../../aspose.slides/textframe/) 中的右侧边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。读取 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | 返回 [TextFrame](../../aspose.slides/textframe/) 中的顶部边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。读取 **double**。 |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | 指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果指定，则此旋转独立于形状，即形状可以具有旋转，同时文本本身也可以有旋转。最终的可视文本旋转值由此属性与属性 TextVerticalType 中的预定义垂直类型综合得出。读取 **float**。 |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 确定文本方向。可视文本旋转的最终值由此属性与属性 RotationAngle 中的自定义角度综合得出。阅读 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** 如果文本在 [TextFrame](../../aspose.slides/textframe/) 的边距处换行。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2007/2013 中完全支持）。阅读 [NullableBool](../../aspose.slides/nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许对子类进行拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许对子类进行拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | 在 [TextFrame](../../aspose.slides/textframe/) 中设置垂直锚点文本。写入 [TextAnchorType](../../aspose.slides/textanchortype/)。 |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | 设置文本的自动适配模式。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。写入 [TextAutofitType](../../aspose.slides/textautofittype/)。 |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | 如果 [NullableBool::True](../../aspose.slides/nullablebool/)，则文本应在框中水平居中。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中设置底部边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。写入 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中设置左侧边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。写入 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中设置右侧边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。写入 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中设置顶部边距（点）。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无影响）。写入 **double**。 |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | 指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果指定，则此旋转独立于形状，即形状可以具有旋转，同时文本本身也可以有旋转。最终的可视文本旋转值由此属性与属性 TextVerticalType 中的预定义垂直类型综合得出。写入 **float**。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | 确定文本方向。可视文本旋转的最终值由此属性与属性 RotationAngle 中的自定义角度综合得出。写入 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)。 |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** 如果文本在 [TextFrame](../../aspose.slides/textframe/) 的边距处换行。更改此属性仅会对以下图表部分产生一定影响：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2007/2013 中完全支持）。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)