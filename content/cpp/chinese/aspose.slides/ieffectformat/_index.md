---
title: IEffectFormat
second_title: Aspose.Slides C++ API 参考文档
description: 表示形状的效果属性。
type: docs
weight: 2029
url: /zh/aspose.slides/ieffectformat/
---
## IEffectFormat 类

表示形状的效果属性。

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## 方法

| Method | Description |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | 禁用模糊效果。 |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | 禁用填充叠加效果。 |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | 禁用辉光效果。 |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | 禁用内部阴影效果。 |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | 禁用外部阴影效果。 |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | 禁用预设阴影效果。 |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | 禁用反射效果。 |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | 禁用柔边效果。 |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | 启用填充叠加效果。 |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | 启用辉光效果。 |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | 启用内部阴影效果。 |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | 启用外部阴影效果。 |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | 启用预设阴影效果。 |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | 启用反射效果。 |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | 启用柔边效果。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 也被视为相等（ IEC 60559:1989 将 NaN 定义为不等于任何值，包括 NaN 本身）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 也被视为相等（ IEC 60559:1989 将 NaN 定义为不等于任何值，包括 NaN 本身）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | 模糊效果。读取 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | 填充叠加效果。读取 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | 辉光效果。读取 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | 内部阴影。读取 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | 若所有效果均已禁用（即新创建的默认 [EffectFormat](../effectformat/) 对象），返回 true。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | 外部阴影。读取 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | 预设阴影。读取 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | 反射。读取 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | 柔边。读取 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | 获取已应用继承的有效效果格式化数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为目标类型描述的实例。相当于 C# 的 `is` 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 守护对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类似实现。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用 nullptr 与值类型对象进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | 模糊效果。写入 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | 填充叠加效果。写入 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | 辉光效果。写入 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | 内部阴影。写入 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | 外部阴影。写入 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | 预设阴影。写入 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | 反射。写入 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | 柔边。写入 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | 设置模糊效果。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针），允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前的共享引用计数值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类似实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 语法。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 守护对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IEffectParamSource](../ieffectparamsource/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)