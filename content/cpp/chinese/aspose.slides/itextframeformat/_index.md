---
title: ITextFrameFormat
second_title: Aspose.Slides for C++ API 参考
description: 包含 TextFrame 的格式属性。
type: docs
weight: 4083
url: /zh/aspose.slides/itextframeformat/
---
## ITextFrameFormat 类

包含 [TextFrame](../textframe/) 的格式属性。

```cpp
class ITextFrameFormat : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | 返回 [TextFrame](../textframe/) 中的垂直锚文本。阅读 [TextAnchorType](../textanchortype/)。 |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | 返回文本的自动适应模式。阅读 [TextAutofitType](../textautofittype/)。 |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | 如果 [NullableBool::True](../nullablebool/)，则文本应在框内水平居中。阅读 [NullableBool](../nullablebool/)。 |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | 返回文本区域的列数。此值必须为正数。否则，将被设置为零。值 0 表示未定义值。阅读 **int32_t**。 |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | 返回文本区域列之间的间距（以点为单位）。仅在存在多个列时适用。此值必须为正数。否则，将被设置为零。阅读 **double**。 |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | 返回或设置完全将文本排除在 3D 场景之外。阅读 **bool**。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | 返回 [TextFrame](../textframe/) 中的底部边距（点）。阅读 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | 返回 [TextFrame](../textframe/) 中的左侧边距（点）。阅读 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | 返回 [TextFrame](../textframe/) 中的右侧边距（点）。阅读 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | 返回 [TextFrame](../textframe/) 中的顶部边距（点）。阅读 **double**。 |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | 指定应用于文本在边界框内的自定义旋转。如果未指定，则使用附随形状的旋转。如果指定，则该旋转独立于形状。即形状可以有一个旋转，同时文本本身也可以有一个旋转。此属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的最终值。阅读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | 返回文本的样式。只读 [ITextStyle](../itextstyle/)。 |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 确定文本方向。此属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的最终值。阅读 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | 返回表示文本 3D 效果属性的 [ThreeDFormat](../threedformat/) 对象。只读 [IThreeDFormat](../ithreedformat/)。 |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | 获取文本换行形状。阅读 [TextShapeType](../textshapetype/)。 |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** 如果文本在 [TextFrame](../textframe/) 的边距处换行。阅读 [NullableBool](../nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | 获取应用继承后的有效文本框格式化数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类进行复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类进行复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | 在 [TextFrame](../textframe/) 中设置垂直锚文本。写入 [TextAnchorType](../textanchortype/)。 |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | 设置文本的自动适应模式。写入 [TextAutofitType](../textautofittype/)。 |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | 如果 [NullableBool::True](../nullablebool/)，则文本应在框内水平居中。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | 设置文本区域的列数。此值必须为正数。否则，将被设置为零。值 0 表示未定义值。写入 **int32_t**。 |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | 设置文本区域列之间的间距（以点为单位）。仅在存在多个列时适用。此值必须为正数。否则，将被设置为零。写入 **double**。 |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | 返回或设置完全将文本排除在 3D 场景之外。写入 **bool**。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | 设置 [TextFrame](../textframe/) 中的底部边距（点）。写入 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | 设置 [TextFrame](../textframe/) 中的左侧边距（点）。写入 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | 设置 [TextFrame](../textframe/) 中的右侧边距（点）。写入 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | 设置 [TextFrame](../textframe/) 中的顶部边距（点）。写入 **double**。 |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | 指定应用于文本在边界框内的自定义旋转。如果未指定，则使用附随形状的旋转。如果指定，则该旋转独立于形状。即形状可以有一个旋转，同时文本本身也可以有一个旋转。此属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的最终值。写入 **float**。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 确定文本方向。此属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的最终值。写入 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | 设置文本换行形状。写入 [TextShapeType](../textshapetype/)。 |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** 如果文本在 [TextFrame](../textframe/) 的边距处换行。写入 [NullableBool](../nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而不是共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)