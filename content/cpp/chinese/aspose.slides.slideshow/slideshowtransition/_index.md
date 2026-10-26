---
title: SlideShowTransition
second_title: Aspose.Slides for C++ API 参考
description: 表示幻灯片放映过渡。
type: docs
weight: 404
url: /zh/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition 类

表示幻灯片放映过渡。

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 确定两个 [SlideShowTransition](./) 实例是否相等。读取/写入 **bool**。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | 此属性指定幻灯片放映是否在一定时间后自动移动到下一张幻灯片。读取 **bool**。 |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | 指定过渡应在多少毫秒后开始。此设置可与 advClick 属性一起使用。如果未指定此属性，则假定不会自动前进。读取 **uint32_t**。 |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | 指定鼠标点击是否会前进幻灯片。如果未指定此属性，则假定值为 true。读取 **bool**。 |
| **int32_t** [get_Duration](./get_duration/)() override | 获取幻灯片过渡效果的持续时间（毫秒）。读取 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | 返回嵌入的音频数据。读取 [IAudio](../../aspose.slides/iaudio/)。 |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | 指定此声音是否为内置声音。如果此属性设为 true，则生成应用程序会被提示检查此声音在其内置声音列表中指定的 name 属性，并可据此显示自定义名称或 UI。读取 **bool**。 |
| **bool** [get_SoundLoop](./get_soundloop/)() override | 此属性指定声音是否会循环播放，直到幻灯片中出现下一个声音事件。读取 **bool**。 |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | 设置或返回幻灯片过渡的声音模式。读取 [TransitionSoundMode](../transitionsoundmode/)。 |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | 为过渡声音指定一个可读的名称。必须为 [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) 赋值才能获取或设置声音名称。读取 [System::String](../../system/string/)。 |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | 指定从当前幻灯片到下一张过渡时使用的过渡速度。读取 [TransitionSpeed](../transitionspeed/)。 |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | 过渡类型。读取 [TransitionType](../transitiontype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) 显示过渡值。只读 [ITransitionValueBase](../itransitionvaluebase/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 充当特定类型的散列函数，适用于哈希算法和散列表等数据结构。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | 此属性指定幻灯片放映是否在一定时间后自动移动到下一张幻灯片。写入 **bool**。 |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | 指定过渡应在多少毫秒后开始。此设置可与 advClick 属性一起使用。如果未指定此属性，则假定不会自动前进。写入 **uint32_t**。 |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | 指定鼠标点击是否会前进幻灯片。如果未指定此属性，则假定值为 true。写入 **bool**。 |
| void [set_Duration](./set_duration/)(**int32_t**) override | 设置幻灯片过渡效果的持续时间（毫秒）。写入 **int32_t**。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | 设置嵌入的音频数据。写入 [IAudio](../../aspose.slides/iaudio/)。 |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | 指定此声音是否为内置声音。如果此属性设为 true，则生成应用程序会被提示检查此声音在其内置声音列表中指定的 name 属性，并可据此显示自定义名称或 UI。写入 **bool**。 |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | 此属性指定声音是否会循环播放，直到幻灯片中出现下一个声音事件。写入 **bool**。 |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | 设置或返回幻灯片过渡的声音模式。写入 [TransitionSoundMode](../transitionsoundmode/)。 |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | 为过渡声音指定一个可读的名称。必须为 [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) 赋值才能获取或设置声音名称。写入 [System::String](../../system/string/)。 |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | 指定从当前幻灯片到下一张过渡时使用的过渡速度。写入 [TransitionSpeed](../transitionspeed/)。 |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | 过渡类型。写入 [TransitionType](../transitiontype/)。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 将第 n 个模板参数设置为弱指针（而非 shared）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [DomObject](../../aspose.slides/domobject/)
* 类 [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* 命名空间 [Aspose::Slides::SlideShow](../)
* 库 [Aspose.Slides](../../)