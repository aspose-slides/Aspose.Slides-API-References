---
title: Reflection
second_title: Aspose.Slides C++ API 参考
description: 表示一个 Reflection 效果。
type: docs
weight: 1067
url: /zh/aspose.slides.effects/reflection/
---
## Reflection 类

Represents a [Reflection](./) effect.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 确定指定的 [Reflection](./) 是否等于当前的 [Reflection](./)。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) 半径。读取 **double**。 |
| **float** [get_Direction](./get_direction/)() override | 反射方向。读取 **float**。 |
| **double** [get_Distance](./get_distance/)() override | 反射距离。读取 **double**。 |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | 指定终止 alpha 值（百分比）的结束位置（沿 alpha 渐变斜坡）。读取 **float**。 |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | 终止反射不透明度。（百分比）。读取 **float**。 |
| **float** [get_FadeDirection](./get_fadedirection/)() override | 指定偏移反射的方向。（角度）。读取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 返回父 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。只读 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 矩形对齐。读取 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | 指定当形状旋转时，反射是否应随形状旋转。读取 **bool**。 |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 指定水平缩放因子，负缩放会导致翻转。（百分比）读取 **double**。 |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 指定垂直缩放因子，负缩放会导致翻转。（百分比）读取 **double**。 |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | 指定水平倾斜角度。读取 **double**。 |
| **double** [get_SkewVertical](./get_skewvertical/)() override | 指定垂直倾斜角度。读取 **double**。 |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 渐变斜坡）。读取 **float**。 |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | 起始反射不透明度。（百分比）。读取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | 版本。只读 **uint32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效 [Reflection](./) 效果数据。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 充当特定类型的哈希函数。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许对子类进行复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许对子类进行复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) 半径。写入 **double**。 |
| void [set_Direction](./set_direction/)(**float**) override | 反射方向。写入 **float**。 |
| void [set_Distance](./set_distance/)(**double**) override | 反射距离。写入 **double**。 |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | 指定终止 alpha 值（百分比）的结束位置（沿 alpha 渐变斜坡）。写入 **float**。 |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | 终止反射不透明度。（百分比）。写入 **float**。 |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | 指定偏移反射的方向。（角度）。写入 **float**。 |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 矩形对齐。写入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | 指定当形状旋转时，反射是否应随形状旋转。写入 **bool**。 |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 指定水平缩放因子，负缩放会导致翻转。（百分比）写入 **double**。 |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 指定垂直缩放因子，负缩放会导致翻转。（百分比）写入 **double**。 |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | 指定水平倾斜角度。写入 **double**。 |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | 指定垂直倾斜角度。写入 **double**。 |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 渐变斜坡）。写入 **float**。 |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | 起始反射不透明度。（百分比）。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IReflection](../ireflection/)
* 类 [IVisualEffect](../ivisualeffect/)
* 类 [IPVIObject](../../aspose.slides/ipviobject/)
* 命名空间 [Aspose::Slides::Effects](../)
* 库 [Aspose.Slides](../../)