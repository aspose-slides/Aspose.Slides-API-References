---
title: IColorFormat
second_title: Aspose.Slides C++ API 参考
description: 表示在演示文稿中使用的颜色。
type: docs
weight: 1691
url: /zh/aspose.slides/icolorformat/
---
## IColorFormat 类

表示在演示文稿中使用的颜色。

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | 从 "color" 复制颜色格式。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **uint8_t** [get_B](./get_b/)() | 返回颜色的蓝色分量。所有颜色变换均被忽略。读取 **uint8_t**。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | 返回结果颜色（已应用所有颜色变换）。设置 RGB 颜色并清除所有颜色变换。读取 [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | 返回在指定索引处应用于颜色的颜色变换操作。读取/写入 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | 返回应用于颜色的颜色变换集合。只读 [IColorOperationCollection](../icoloroperationcollection/)。 |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | 返回颜色定义方法。读取 [Slides::ColorType](../colortype/)。 |
| virtual **float** [get_FloatB](./get_floatb/)() | 返回颜色的蓝色分量。所有颜色变换均被忽略。读取 **float**。 |
| virtual **float** [get_FloatG](./get_floatg/)() | 返回颜色的绿色分量。所有颜色变换均被忽略。读取 **float**。 |
| virtual **float** [get_FloatR](./get_floatr/)() | 返回颜色的红色分量。所有颜色变换均被忽略。读取 **float**。 |
| virtual **uint8_t** [get_G](./get_g/)() | 返回颜色的绿色分量。所有颜色变换均被忽略。读取 **uint8_t**。 |
| virtual **float** [get_Hue](./get_hue/)() | 返回颜色在 HSL 表示中的色相分量。所有颜色变换均被忽略。读取 **float**。 |
| virtual **float** [get_Luminance](./get_luminance/)() | 返回颜色在 HSL 表示中的亮度分量。所有颜色变换均被忽略。读取 **float**。 |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | 返回颜色预设。读取 [Slides::PresetColor](../presetcolor/)。 |
| virtual **uint8_t** [get_R](./get_r/)() | 返回颜色的红色分量。所有颜色变换均被忽略。读取 **uint8_t**。 |
| virtual **float** [get_Saturation](./get_saturation/)() | 返回颜色在 HSL 表示中的饱和度分量。所有颜色变换均被忽略。读取 **float**。 |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | 返回由配色方案标识的颜色。读取 [Slides::SchemeColor](../schemecolor/)。 |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | 返回由系统颜色表标识的颜色。读取 [Slides::SystemColor](../systemcolor/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 string 和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [set_B](./set_b/)(**uint8_t**) | 设置颜色的蓝色分量。所有颜色变换均被忽略。写入 **uint8_t**。 |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | 返回结果颜色（已应用所有颜色变换）。设置 RGB 颜色并清除所有颜色变换。写入 [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | 设置在指定索引处应用于颜色的颜色变换操作。读取/写入 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | 设置颜色定义方法。写入 [Slides::ColorType](../colortype/)。 |
| virtual void [set_FloatB](./set_floatb/)(**float**) | 设置颜色的蓝色分量。所有颜色变换均被忽略。写入 **float**。 |
| virtual void [set_FloatG](./set_floatg/)(**float**) | 设置颜色的绿色分量。所有颜色变换均被忽略。写入 **float**。 |
| virtual void [set_FloatR](./set_floatr/)(**float**) | 设置颜色的红色分量。所有颜色变换均被忽略。写入 **float**。 |
| virtual void [set_G](./set_g/)(**uint8_t**) | 设置颜色的绿色分量。所有颜色变换均被忽略。写入 **uint8_t**。 |
| virtual void [set_Hue](./set_hue/)(**float**) | 设置颜色在 HSL 表示中的色相分量。所有颜色变换均被忽略。写入 **float**。 |
| virtual void [set_Luminance](./set_luminance/)(**float**) | 设置颜色在 HSL 表示中的亮度分量。所有颜色变换均被忽略。写入 **float**。 |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | 设置颜色预设。写入 [Slides::PresetColor](../presetcolor/)。 |
| virtual void [set_R](./set_r/)(**uint8_t**) | 设置颜色的红色分量。所有颜色变换均被忽略。写入 **uint8_t**。 |
| virtual void [set_Saturation](./set_saturation/)(**float**) | 设置颜色在 HSL 表示中的饱和度分量。所有颜色变换均被忽略。写入 **float**。 |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | 设置由配色方案标识的颜色。写入 [Slides::SchemeColor](../schemecolor/)。 |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | 设置由系统颜色表标识的颜色。写入 [Slides::SystemColor](../systemcolor/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | 返回一个表示当前颜色格式的 [System::String](../../system/string/)。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IFillParamSource](../ifillparamsource/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)