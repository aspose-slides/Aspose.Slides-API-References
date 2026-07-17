---
title: BulletFormat
second_title: Aspose.Slides C++ API 参考
description: 表示段落项目符号格式属性。
type: docs
weight: 248
url: /zh/aspose.slides/bulletformat/
---
## BulletFormat 类

表示段落项目符号格式属性。

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## 方法

| Method | Description |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | 设置默认的非零偏移，以在启用项目符号时对有效段落的 Indent 和 MarginLeft 生效（类似于在 PowerPoint 中启用段落项目符号/编号时的行为）。如果禁用项目符号，则仅重置段落的 Indent 和 MarginLeft（类似于在 PowerPoint 中禁用段落项目符号/编号时的行为）。缩进偏移相对于当前项目符号上下文（IBulletFormat::get(set)_Type、.NumberedBulletStyle 和第一段落部分的 FontHeight）进行应用。非零缩进偏移被应用到当前段落的有效 Indent 和 MarginLeft（使结果值为局部值）。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象进行比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 对任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 对任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| char16_t [get_Char](./get_char/)() override | 返回段落的项目符号字符，且不继承。读取 **wchar_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | 返回段落的项目符号的颜色格式，且不继承。只读 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | 返回段落的项目符号字体，且不继承。读取 [IFontData](../ifontdata/)。 |
| **float** [get_Height](./get_height/)() override | 返回段落的项目符号高度，且不继承。值 std::numeric_limits<float>::quiet_NaN() 表示项目符号从段落的第一部分继承高度。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | 确定项目符号是否具有自己的颜色或从段落的第一部分继承颜色。如果项目符号具有自己的颜色，则为 **[NullableBool::True](../nullablebool/)**；如果从段落的第一部分继承颜色，则为 **[NullableBool::False](../nullablebool/)**。读取 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | 确定项目符号是否具有自己的字体或从段落的第一部分继承字体。如果项目符号具有自己的字体，则为 **[NullableBool::True](../nullablebool/)**；如果从段落的第一部分继承字体，则为 **[NullableBool::False](../nullablebool/)**。读取 [NullableBool](../nullablebool/)。 |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | 返回未继承的编号项目符号组使用的起始编号。读取 **int16_t**。 |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | 返回未继承的编号项目符号的样式。读取 [Slides::NumberedBulletStyle](../numberedbulletstyle/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 返回段落中用作项目符号的图片，且不继承。只读 [ISlidesPicture](../islidespicture/)。 |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | 返回段落的项目符号类型，且不继承。读取 [BulletType](../bullettype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效项目符号格式化数据。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是由 targetType 描述的类型的实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许拷贝构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许拷贝构造子类。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_Char](./set_char/)(char16_t) override | 设置段落的项目符号字符，且不继承。写入 **wchar_t**。 |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置段落的项目符号字体，且不继承。写入 [IFontData](../ifontdata/)。 |
| void [set_Height](./set_height/)(**float**) override | 设置段落的项目符号高度，且不继承。值 std::numeric_limits<float>::quiet_NaN() 表示项目符号从段落的第一部分继承高度。写入 **float**。 |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | 确定项目符号是否具有自己的颜色或从段落的第一部分继承颜色。如果项目符号具有自己的颜色，则为 **[NullableBool::True](../nullablebool/)**；如果从段落的第一部分继承颜色，则为 **[NullableBool::False](../nullablebool/)**。写入 [NullableBool](../nullablebool/)。 |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | 确定项目符号是否具有自己的字体或从段落的第一部分继承字体。如果项目符号具有自己的字体，则为 **[NullableBool::True](../nullablebool/)**；如果从段落的第一部分继承字体，则为 **[NullableBool::False](../nullablebool/)**。写入 [NullableBool](../nullablebool/)。 |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | 设置未继承的编号项目符号组使用的起始编号。写入 **int16_t**。 |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | 设置未继承的编号项目符号的样式。写入 [Slides::NumberedBulletStyle](../numberedbulletstyle/)。 |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | 设置段落的项目符号类型，且不继承。写入 [BulletType](../bullettype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换到弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [PVIObject](../pviobject/)
* 类 [IBulletFormat](../ibulletformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)