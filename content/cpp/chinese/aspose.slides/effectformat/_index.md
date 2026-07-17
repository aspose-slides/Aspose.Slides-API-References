---
title: EffectFormat
second_title: Aspose.Slides C++ API 参考
description: 表示形状的效果属性。
type: docs
weight: 846
url: /zh/aspose.slides/effectformat/
---
## EffectFormat 类

表示形状的效果属性。

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | 禁用模糊效果。 |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | 禁用填充覆盖效果。 |
| void [DisableGlowEffect](./disablegloweffect/)() override | 禁用辉光效果。 |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | 禁用内阴影效果。 |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | 禁用外阴影效果。 |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | 禁用预设阴影效果。 |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | 禁用反射效果。 |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | 禁用柔和边缘效果。 |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | 启用填充覆盖效果。 |
| void [EnableGlowEffect](./enablegloweffect/)() override | 启用辉光效果。 |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | 启用内阴影效果。 |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | 启用外阴影效果。 |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | 启用预设阴影效果。 |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | 启用反射效果。 |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | 启用柔和边缘效果。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象进行比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | 模糊效果。读取 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | 填充覆盖效果。读取 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | 辉光效果。读取 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | 内阴影。读取 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | 如果所有效果均已禁用（如刚创建的默认 [EffectFormat](./) 对象），则返回 true。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | 外阴影。读取 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | 预设阴影。读取 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | 反射。读取 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | 柔和边缘。读取 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | 获取已应用继承的有效效果格式化数据。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许对派生类进行复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许对派生类进行复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | 模糊效果。写入 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | 填充覆盖效果。写入 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | 辉光效果。写入 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | 内阴影。写入 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | 外阴影。写入 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | 预设阴影。写入 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | 反射。写入 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | 柔和边缘。写入 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | 设置模糊效果。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [PVIObject](../pviobject/)
* 类 [IEffectFormat](../ieffectformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)