---
title: IViewProperties
second_title: Aspose.Slides for C++ API 参考
description: 演示文稿的宽视图属性。
type: docs
weight: 4239
url: /zh/aspose.slides/iviewproperties/
---
## IViewProperties 类

[Presentation](../presentation/) 宽视图属性。

```cpp
class IViewProperties : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| virtual **float** [get_GridSpacing](./get_gridspacing/)() | 返回用于演示文稿文档底层网格的网格间距，单位为点。读取 **float**。 |
| virtual [ViewType](../viewtype/) [get_LastView](./get_lastview/)() | 指定用于上次保存演示文稿文档的视图模式。读取 [ViewType](../viewtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewProperties](../inormalviewproperties/)\> [get_NormalViewProperties](./get_normalviewproperties/)() | 表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。只读 [INormalViewProperties](../inormalviewproperties/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommonSlideViewProperties](../icommonslideviewproperties/)\> [get_NotesViewProperties](./get_notesviewproperties/)() | 指定与备注视图模式关联的通用视图属性。只读 [ICommonSlideViewProperties](../icommonslideviewproperties/)。 |
| virtual [NullableBool](../nullablebool/) [get_ShowComments](./get_showcomments/)() | 指定是否应显示幻灯片批注。读取 [NullableBool](../nullablebool/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommonSlideViewProperties](../icommonslideviewproperties/)\> [get_SlideViewProperties](./get_slideviewproperties/)() | 指定与幻灯片视图模式关联的通用视图属性。只读 [ICommonSlideViewProperties](../icommonslideviewproperties/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。C# [System.Object.GetType()](../../system/object/gettype/) 调用的类似实现。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。C# 'is' 运算符的类似实现。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类似实现。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 通过引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_GridSpacing](./set_gridspacing/)(**float**) | 设置用于演示文稿文档底层网格的网格间距，单位为点。写入 **float**。 |
| virtual void [set_LastView](./set_lastview/)([ViewType](../viewtype/)) | 指定用于上次保存演示文稿文档的视图模式。写入 [ViewType](../viewtype/)。 |
| virtual void [set_ShowComments](./set_showcomments/)([NullableBool](../nullablebool/)) | 指定是否应显示幻灯片批注。写入 [NullableBool](../nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而不是共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类似实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)