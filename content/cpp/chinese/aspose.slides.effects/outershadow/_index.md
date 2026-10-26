---
title: OuterShadow
second_title: Aspose.Slides C++ API 参考
description: 表示外部阴影效果。
type: docs
weight: 1041
url: /zh/aspose.slides.effects/outershadow/
---
## OuterShadow 类

表示外部阴影效果。

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 确定指定的 [OuterShadow](./) 是否等于当前的 [OuterShadow](./)。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) 半径，单位为点。默认值 \\u2013 0 pt。读取 **double**。 |
| **float** [get_Direction](./get_direction/)() override | 阴影方向，单位为度。默认值 \\u2013 0 \\u00B0（从左到右）。读取 **float**。 |
| **double** [get_Distance](./get_distance/)() override | 阴影与对象的距离，单位为点。默认值 \\u2013 0 pt。读取 **double**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。只读 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 矩形对齐方式。默认值 \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。读取 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | 指示阴影是否随形状一起旋转。默认值 \\u2013 true。读取 **bool**。 |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 水平缩放因子，原始尺寸的百分比。负比例会导致翻转。默认值 \\u2013 100 %. 读取 **double**。 |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 垂直缩放因子，原始尺寸的百分比。负比例会导致翻转。默认值 \\u2013 100 %. 读取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | 阴影颜色。默认值 \\u2013 自动黑色（取决于主题）。只读 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | 水平倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。读取 **double**。 |
| **double** [get_SkewVertical](./get_skewvertical/)() override | 垂直倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。读取 **double**。 |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | 版本。只读 **uint32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效 Outer Shadow 效果数据。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 作为特定类型的哈希函数。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) 半径，单位为点。默认值 \\u2013 0 pt。写入 **double**。 |
| void [set_Direction](./set_direction/)(**float**) override | 阴影方向，单位为度。默认值 \\u2013 0 \\u00B0（从左到右）。写入 **float**。 |
| void [set_Distance](./set_distance/)(**double**) override | 阴影与对象的距离，单位为点。默认值 \\u2013 0 pt。写入 **double**。 |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 矩形对齐方式。默认值 \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。写入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | 指示阴影是否随形状一起旋转。默认值 \\u2013 true。写入 **bool**。 |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 水平缩放因子，原始尺寸的百分比。负比例会导致翻转。默认值 \\u2013 100 %. 写入 **double**。 |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 垂直缩放因子，原始尺寸的百分比。负比例会导致翻转。默认值 \\u2013 100 %. 写入 **double**。 |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | 水平倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。写入 **double**。 |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | 垂直倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。写入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IOuterShadow](../ioutershadow/)
* 类 [IVisualEffect](../ivisualeffect/)
* 类 [IPVIObject](../../aspose.slides/ipviobject/)
* 命名空间 [Aspose::Slides::Effects](../)
* 库 [Aspose.Slides](../../)