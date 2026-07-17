---
title: IBulletFormat
second_title: Aspose.Slides C++ API 参考
description: 表示段落项目符号格式属性。
type: docs
weight: 1561
url: /zh/aspose.slides/ibulletformat/
---
## IBulletFormat 类

表示段落项目符号格式属性。

```cpp
class IBulletFormat : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | 设置默认的非零位移，以在启用项目符号时为有效段落 Indent 和 MarginLeft 提供效果（类似 PowerPoint 在启用段落项目符号/编号时的行为）。如果禁用项目符号，则仅重置段落 Indent 和 MarginLeft（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。位移相对于当前项目符号上下文（IBulletFormat::get(set)_Type、.NumberedBulletStyle 和第一部分的 FontHeight）进行应用。非零位移会应用于当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿 C# 的浮点比较，其中两个 NaN 被视为相等，尽管 IEC 60559:1989 中 NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿 C# 的浮点比较，其中两个 NaN 被视为相等，尽管 IEC 60559:1989 中 NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual char16_t [get_Char](./get_char/)() | 返回段落的项目符号字符（无继承）。读取 **wchar_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | 返回段落项目符号的颜色格式（无继承）。只读 [IColorFormat](../icolorformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | 返回段落项目符号的字体（无继承）。读取 [IFontData](../ifontdata/)。 |
| virtual **float** [get_Height](./get_height/)() | 返回段落项目符号的高度（无继承）。值 std::numeric_limits<float>::quiet_NaN() 表示项目符号从段落的第一部分继承高度。读取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | 确定项目符号是否拥有自己的颜色或从段落的第一部分继承颜色。**[NullableBool::True](../nullablebool/)** 表示项目符号拥有自己的颜色，**[NullableBool::False](../nullablebool/)** 表示项目符号从第一部分继承颜色。读取 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | 确定项目符号是否拥有自己的字体或从段落的第一部分继承字体。**[NullableBool::True](../nullablebool/)** 表示项目符号拥有自己的字体，**[NullableBool::False](../nullablebool/)** 表示项目符号从第一部分继承字体。读取 [NullableBool](../nullablebool/)。 |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | 返回用于编号项目符号组的第一个数字（无继承）。读取 **int16_t**。 |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | 返回编号项目符号的样式（无继承）。读取 [NumberedBulletStyle](../numberedbulletstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 返回段落中用作项目符号的图片（无继承）。只读 [ISlidesPicture](../islidespicture/)。 |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | 返回段落项目符号的类型（无继承）。读取 [BulletType](../bullettype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | 获取已应用继承的有效项目符号格式化数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许复制构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许复制构造子类。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Char](./set_char/)(char16_t) | 设置段落的项目符号字符（无继承）。写入 **wchar_t**。 |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 设置段落的项目符号字体（无继承）。写入 [IFontData](../ifontdata/)。 |
| virtual void [set_Height](./set_height/)(**float**) | 设置段落的项目符号高度（无继承）。值 std::numeric_limits<float>::quiet_NaN() 决定项目符号从段落的第一部分继承高度。写入 **float**。 |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | 确定项目符号是否拥有自己的颜色或从段落的第一部分继承颜色。若项目符号拥有自己的颜色，则 **[NullableBool::True](../nullablebool/)**；若项目符号从第一部分继承颜色，则 **[NullableBool::False](../nullablebool/)**。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | 确定项目符号是否拥有自己的字体或从段落的第一部分继承字体。若项目符号拥有自己的字体，则 **[NullableBool::True](../nullablebool/)**；若项目符号从第一部分继承字体，则 **[NullableBool::False](../nullablebool/)**。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | 设置用于编号项目符号组的第一个数字（无继承）。写入 **int16_t**。 |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | 设置编号项目符号的样式（无继承）。写入 [NumberedBulletStyle](../numberedbulletstyle/)。 |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | 设置段落的项目符号类型（无继承）。写入 [BulletType](../bullettype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)