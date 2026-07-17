---
title: ImageTransformOperationFactory
second_title: Aspose.Slides C++ API 参考
description: 允许创建图像变换操作
type: docs
weight: 859
url: /zh/aspose.slides.effects/imagetransformoperationfactory/
---
## ImageTransformOperationFactory 类

允许创建图像变换操作

```cpp
class ImageTransformOperationFactory : public Aspose::Slides::Effects::IImageTransformOperationFactory
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [CreateAlphaBiLevel](./createalphabilevel/)(**float**) override | 创建 Alpha [BiLevel](../bilevel/) 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [CreateAlphaFloor](./createalphafloor/)() override | 创建 Alpha floor 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [CreateAlphaInverse](./createalphainverse/)() override | 创建 Alpha inverse 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [CreateAlphaModulate](./createalphamodulate/)() override | 创建 Alpha modulate 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [CreateAlphaModulateFixed](./createalphamodulatefixed/)(**float**) override | 创建 Alpha modulate fixed 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [CreateAlphaReplace](./createalphareplace/)(**float**) override | 创建 Alpha replace 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [CreateAlphCeiling](./createalphceiling/)() override | 创建 Alpha Ceiling 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [CreateBiLevel](./createbilevel/)(**float**) override | 创建 [BiLevel](../bilevel/) 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [CreateBlur](./createblur/)(**double**, **bool**) override | 创建 [Blur](../blur/) 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [CreateColorChange](./createcolorchange/)() override | 创建 Color change 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [CreateColorReplace](./createcolorreplace/)() override | 创建 Color replace 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [CreateDuotone](./createduotone/)() override | 创建 [Duotone](../duotone/) 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [CreateFillOverlay](./createfilloverlay/)() override | 创建 Fill overlay 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [CreateGrayScale](./creategrayscale/)() override | 创建 Gray scale 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [CreateHSL](./createhsl/)(**float**, **float**, **float**) override | 创建 Hue Saturation [Luminance](../luminance/) 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [CreateLuminance](./createluminance/)(**float**, **float**) override | 创建 [Luminance](../luminance/) 效果。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [CreateTint](./createtint/)(**float**, **float**) override | 创建 [Tint](../tint/) 效果。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比较对象，使用 C# [Object.Equals](../../system/object/equals/) 语义。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | 比较引用类型对象，采用 C# 风格。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | 比较值类型对象，采用 C# 风格。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | 模拟 C# 风格的浮点比较，当两个 NaN 被视为相等，即使根据 IEC 60559:1989 NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | 模拟 C# 风格的浮点比较，当两个 NaN 被视为相等，即使根据 IEC 60559:1989 NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | 仅供内部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

用于 COM 兼容性。 

## 另请参见

* 类 [IImageTransformOperationFactory](../iimagetransformoperationfactory/)
* 命名空间 [Aspose::Slides::Effects](../)
* 库 [Aspose.Slides](../../)