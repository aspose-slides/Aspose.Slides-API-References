---
title: Hyperlink
second_title: Aspose.Slides for C++ API 参考
description: 表示一个超链接。
type: docs
weight: 1236
url: /zh/aspose.slides/hyperlink/
---
## Hyperlink 类

表示一个超链接。

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 确定两个 [Hyperlink](./) 实例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | 返回 [Hyperlink](./) 的操作类型。只读 [HyperlinkActionType](../hyperlinkactiontype/)。 |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | 表示超链接颜色的来源——样式或部分格式。只读 [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | 返回结束演示的超链接。只读 [Hyperlink](./)。 |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | 指定外部 URL。只读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | 表示为该部分设置的超链接，而不考虑该部分的实际内容。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | 返回指向演示文稿第一张幻灯片的超链接。只读 [Hyperlink](./)。 |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | 确定在点击时是否应突出显示超链接。只读 **bool**。 |
| **bool** [get_History](./get_history/)() override | 确定在调用时是否将父超链接的目标添加到已查看超链接列表中。只读 **bool**。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | 返回指向演示文稿最后一张幻灯片的超链接。只读 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | 返回指向最近查看的幻灯片的超链接。只读 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | 返回一个特殊的 “播放媒体文件” 超链接。用于 [AudioFrame](../audioframe/) 和 [VideoFrame](../videoframe/)。只读 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | 返回指向下一张幻灯片的超链接。只读 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | 返回一个特殊的 “不执行任何操作” 超链接。只读 [Hyperlink](./)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | 返回指向前一张幻灯片的超链接。只读 [Hyperlink](./)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | 表示超链接的播放声音。只读 [IAudio](../iaudio/)。 |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | 确定在点击超链接时是否应停止声音。只读 **bool**。 |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | 在存在时返回父 HTML 框架集中父超链接目标的框架。读/写 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | 如果 [Hyperlink](./) 指向特定幻灯片则返回该幻灯片。只读 [ISlide](../islide/)。 |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | 返回可在用户界面中显示的、与父超链接关联的字符串。只读 [System::String](../../system/string/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 作为特定类型的哈希函数，适用于哈希算法和哈希表等数据结构。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | 创建一个超链接实例。 |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | 创建指向特定幻灯片的超链接实例。注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将保存为 NoAction。 |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | 使用另一个超链接作为源创建超链接实例，覆盖次要属性。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | 表示超链接颜色的来源——样式或部分格式。写入 [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | 确定在点击时是否应突出显示超链接。写入 **bool**。 |
| void [set_History](./set_history/)(**bool**) override | 确定在调用时是否将父超链接的目标添加到已查看超链接列表中。写入 **bool**。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 表示超链接的播放声音。写入 [IAudio](../iaudio/)。 |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | 确定在点击超链接时是否应停止声音。写入 **bool**。 |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | 在存在时返回父 HTML 框架集中父超链接目标的框架。读/写 [System::String](../../system/string/)。 |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | 返回可在用户界面中显示的、与父超链接关联的字符串。写入 [System::String](../../system/string/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [PVIObject](../pviobject/)
* 类 [IHyperlink](../ihyperlink/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)