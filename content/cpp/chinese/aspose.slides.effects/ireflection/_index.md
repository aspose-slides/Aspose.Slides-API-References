---
title: IReflection
second_title: Aspose.Slides for C++ API 参考
description: 表示反射效果。
type: docs
weight: 937
url: /zh/aspose.slides.effects/ireflection/
---
## IReflection 类

表示反射效果。

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），也将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），也将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 半径。读取 **double**。 |
| virtual **float** [get_Direction](./get_direction/)() | 反射方向。读取 **float**。 |
| virtual **double** [get_Distance](./get_distance/)() | 反射距离。读取 **double**。 |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | 指定结束 alpha 值（百分比）的结束位置（沿 alpha 梯度坡道）。读取 **float**。 |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | 结束反射不透明度（百分比）。读取 **float**。 |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | 指定偏移反射的方向（角度）。读取 **float**。 |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 矩形对齐。读取 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | 指定当形状旋转时，反射是否随形状旋转。读取 **bool**。 |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 指定水平缩放因子，负的缩放会导致翻转（百分比）。读取 **double**。 |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 指定垂直缩放因子，负的缩放会导致翻转（百分比）。读取 **double**。 |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 指定水平倾斜角度。读取 **double**。 |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 指定垂直倾斜角度。读取 **double**。 |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 梯度坡道）。读取 **float**。 |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | 起始反射不透明度（百分比）。读取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 获取应用继承后的有效数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类比。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。C# [System.Object.GetType()](../../system/object/gettype/) 调用的类比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类比。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 半径。写入 **double**。 |
| virtual void [set_Direction](./set_direction/)(**float**) | 反射方向。写入 **float**。 |
| virtual void [set_Distance](./set_distance/)(**double**) | 反射距离。写入 **double**。 |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | 指定结束 alpha 值（百分比）的结束位置（沿 alpha 梯度坡道）。写入 **float**。 |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | 结束反射不透明度（百分比）。写入 **float**。 |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | 指定偏移反射的方向（角度）。写入 **float**。 |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 矩形对齐。写入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | 指定当形状旋转时，反射是否随形状旋转。写入 **bool**。 |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 指定水平缩放因子，负的缩放会导致翻转（百分比）。写入 **double**。 |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 指定垂直缩放因子，负的缩放会导致翻转（百分比）。写入 **double**。 |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 指定水平倾斜角度。写入 **double**。 |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 指定垂直倾斜角度。写入 **double**。 |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 梯度坡道）。写入 **float**。 |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | 起始反射不透明度（百分比）。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类比。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IImageTransformOperation](../iimagetransformoperation/)
* 类 [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 命名空间 [Aspose::Slides::Effects](../)
* 库 [Aspose.Slides](../../)