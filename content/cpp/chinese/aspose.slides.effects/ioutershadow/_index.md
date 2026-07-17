---
title: IOuterShadow
second_title: Aspose.Slides C++ API 参考
description: 表示外部阴影效果。
type: docs
weight: 885
url: /zh/aspose.slides.effects/ioutershadow/
---
## IOuterShadow 类


Represents an Outer Shadow effect.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## 方法

| 方法 | 说明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 半径，单位为点。默认值 \\u2013 0 pt。只读 **double**。 |
| virtual **float** [get_Direction](./get_direction/)() | 阴影方向，单位为度。默认值 \\u2013 0 \\u00B0（从左到右）。只读 **float**。 |
| virtual **double** [get_Distance](./get_distance/)() | 阴影与对象的距离，单位为点。默认值 \\u2013 0 pt。只读 **double**。 |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 矩形对齐方式。默认值 \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。只读 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | 指示阴影是否随形状一起旋转。默认值 \\u2013 true。只读 **bool**。 |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 横向缩放因子，以原始尺寸的百分比表示。负数缩放会导致翻转。默认值 \\u2013 100%。只读 **double**。 |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 纵向缩放因子，以原始尺寸的百分比表示。负数缩放会导致翻转。默认值 \\u2013 100%。只读 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | 阴影颜色。默认值 \\u2013 自动黑色（受主题影响）。只读 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 横向倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。只读 **double**。 |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 纵向倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。只读 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 获取应用继承后的有效数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型的实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 半径，单位为点。默认值 \\u2013 0 pt。写入 **double**。 |
| virtual void [set_Direction](./set_direction/)(**float**) | 阴影方向，单位为度。默认值 \\u2013 0 \\u00B0（从左到右）。写入 **float**。 |
| virtual void [set_Distance](./set_distance/)(**double**) | 阴影与对象的距离，单位为点。默认值 \\u2013 0 pt。写入 **double**。 |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 矩形对齐方式。默认值 \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。写入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | 指示阴影是否随形状一起旋转。默认值 \\u2013 true。写入 **bool**。 |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 横向缩放因子，以原始尺寸的百分比表示。负数缩放会导致翻转。默认值 \\u2013 100%。写入 **double**。 |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 纵向缩放因子，以原始尺寸的百分比表示。负数缩放会导致翻转。默认值 \\u2013 100%。写入 **double**。 |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 横向倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。写入 **double**。 |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 纵向倾斜角度，单位为度。默认值 \\u2013 0 \\u00B0。写入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另请参阅

* 类 [IImageTransformOperation](../iimagetransformoperation/)
* 类 [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 命名空间 [Aspose::Slides::Effects](../)
* 库 [Aspose.Slides](../../)