---
title: FillFormat
second_title: Aspose.Slides C++ API 参考
description: 表示填充格式选项。
type: docs
weight: 885
url: /zh/aspose.slides/fillformat/
---
## FillFormat 类

表示填充格式选项。

```cpp
class FillFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::IFillFormat
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象进行比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [Aspose::Slides::FillType](../filltype/) [get_FillType](./get_filltype/)() override | 返回填充类型。阅读 [Slides::FillType](../filltype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGradientFormat](../igradientformat/)\> [get_GradientFormat](./get_gradientformat/)() override | 返回渐变填充格式。只读 [IGradientFormat](../igradientformat/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPatternFormat](../ipatternformat/)\> [get_PatternFormat](./get_patternformat/)() override | 返回图案填充格式。只读 [IPatternFormat](../ipatternformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFillFormat](./get_picturefillformat/)() override | 返回图片填充格式。只读 [IPictureFillFormat](../ipicturefillformat/)。 |
| [NullableBool](../nullablebool/) [get_RotateWithShape](./get_rotatewithshape/)() override | 确定填充是否应随形状旋转。读取 [NullableBool](../nullablebool/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_SolidFillColor](./get_solidfillcolor/)() override | 返回填充颜色。只读 [IColorFormat](../icolorformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效填充格式数据。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_FillType](./set_filltype/)([Aspose::Slides::FillType](../filltype/)) override | 设置填充类型。写入 [Slides::FillType](../filltype/)。 |
| void [set_RotateWithShape](./set_rotatewithshape/)([NullableBool](../nullablebool/)) override | 确定填充是否应随形状旋转。写入 [NullableBool](../nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [PVIObject](../pviobject/)
* 类 [IFillFormat](../ifillformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)