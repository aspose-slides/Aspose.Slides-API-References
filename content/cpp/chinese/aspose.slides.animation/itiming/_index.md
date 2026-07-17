---
title: ITiming
second_title: Aspose.Slides for C++ API 参考
description: 表示动画计时。
type: docs
weight: 443
url: /zh/aspose.slides.animation/itiming/
---
## ITiming 类

表示动画计时。

```cpp
class ITiming : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **float** [get_Accelerate](./get_accelerate/)() | 描述加速行为效果的持续时间百分比。读取 **float**。 |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | 描述在正向播放后是否自动以相反方向播放动画。读取 **bool**。 |
| virtual **float** [get_Decelerate](./get_decelerate/)() | 描述减速行为效果的持续时间百分比。读取 **float**。 |
| virtual **float** [get_Duration](./get_duration/)() | 描述动画效果的持续时间。读取 **float**。 |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | 描述效果应重复的次数。读取 **float**。 |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | 描述效果应重复的次数。读取 **float**。 |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | 此属性指定效果是否会重复直到幻灯片结束。读取 **bool**。 |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | 此属性指定效果是否会重复直到下一次点击。读取 **bool**。 |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | 指定效果在完成后是否重新启动。读取 [EffectRestartType](../effectrestarttype/)。 |
| virtual **bool** [get_Rewind](./get_rewind/)() | 此属性指定效果在播放完毕后是否会倒回。读取 **bool**。 |
| virtual **float** [get_Speed](./get_speed/)() | 指定计时加速（或减速）的百分比。读取 **float**。 |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | 描述触发后的延迟时间。读取 **float**。 |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | 描述触发器类型。读取 [EffectTriggerType](../effecttriggertype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | 描述加速行为效果的持续时间百分比。写入 **float**。 |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | 描述在正向播放后是否自动以相反方向播放动画。写入 **bool**。 |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | 描述减速行为效果的持续时间百分比。写入 **float**。 |
| virtual void [set_Duration](./set_duration/)(**float**) | 描述动画效果的持续时间。写入 **float**。 |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | 描述效果应重复的次数。写入 **float**。 |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | 描述效果应重复的次数。写入 **float**。 |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | 此属性指定效果是否会重复直到幻灯片结束。写入 **bool**。 |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | 此属性指定效果是否会重复直到下一次点击。写入 **bool**。 |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | 指定效果在完成后是否重新启动。写入 [EffectRestartType](../effectrestarttype/)。 |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | 此属性指定效果在播放完毕后是否会倒回。写入 **bool**。 |
| virtual void [set_Speed](./set_speed/)(**float**) | 指定计时加速（或减速）的百分比。写入 **float**。 |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | 描述触发后的延迟时间。写入 **float**。 |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | 描述触发器类型。写入 [EffectTriggerType](../effecttriggertype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而不是共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides::Animation](../)
* 库 [Aspose.Slides](../../)