---
title: Timing
second_title: Aspose.Slides for C++ API 参考
description: 表示动画计时。
type: docs
weight: 625
url: /zh/aspose.slides.animation/timing/
---
## Timing 类

表示动画计时。

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值都不相等，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值都不相等，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **float** [get_Accelerate](./get_accelerate/)() override | 描述持续时间加速行为效果的百分比。读取 **float**。 |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | 描述在正向播放后是否自动反向播放动画。读取 **bool**。 |
| **float** [get_Decelerate](./get_decelerate/)() override | 描述持续时间减速行为效果的百分比。读取 **float**。 |
| **float** [get_Duration](./get_duration/)() override | 描述动画效果的持续时间。读取 **float**。 |
| **float** [get_RepeatCount](./get_repeatcount/)() override | 描述效果应重复的次数。读取 **float**。 |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | 描述效果应重复的次数。读取 **float**。 |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | 此属性指定效果是否会重复直到幻灯片结束。读取 **bool**。 |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | 此属性指定效果是否会重复直到下一次点击。读取 **bool**。 |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | 指定效果是否在完成后重新启动。读取 [EffectRestartType](../effectrestarttype/)。 |
| **bool** [get_Rewind](./get_rewind/)() override | 此属性指定效果在播放完成后是否倒回。读取 **bool**。 |
| **float** [get_Speed](./get_speed/)() override | 指定加速（或减速）计时的百分比。读取 **float**。 |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | 描述触发后的延迟时间。读取 **float**。 |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | 描述触发器类型。读取 [EffectTriggerType](../effecttriggertype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_Accelerate](./set_accelerate/)(**float**) override | 描述持续时间加速行为效果的百分比。写入 **float**。 |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | 描述在正向播放后是否自动反向播放动画。写入 **bool**。 |
| void [set_Decelerate](./set_decelerate/)(**float**) override | 描述持续时间减速行为效果的百分比。写入 **float**。 |
| void [set_Duration](./set_duration/)(**float**) override | 描述动画效果的持续时间。写入 **float**。 |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | 描述效果应重复的次数。写入 **float**。 |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | 描述效果应重复的次数。写入 **float**。 |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | 此属性指定效果是否会重复直到幻灯片结束。写入 **bool**。 |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | 此属性指定效果是否会重复直到下一次点击。写入 **bool**。 |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | 指定效果是否在完成后重新启动。写入 [EffectRestartType](../effectrestarttype/)。 |
| void [set_Rewind](./set_rewind/)(**bool**) override | 此属性指定效果在播放完成后是否倒回。写入 **bool**。 |
| void [set_Speed](./set_speed/)(**float**) override | 指定加速（或减速）计时的百分比。写入 **float**。 |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | 描述触发后的延迟时间。写入 **float**。 |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | 描述触发器类型。写入 [EffectTriggerType](../effecttriggertype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* Class [ITiming](../itiming/)
* Class [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Animation](../)
* Library [Aspose.Slides](../../)