---
title: GraphicalObjectLock
second_title: Aspose.Slides C++ API 参考
description: 确定在父 GraphicalObject 上禁用哪些操作。
type: docs
weight: 1184
url: /zh/aspose.slides/graphicalobjectlock/
---
## GraphicalObjectLock 类

确定在父 [GraphicalObject](../graphicalobject/) 上禁用哪些操作。

```cpp
class GraphicalObjectLock : public Aspose::Slides::BaseShapeLock,
                            public Aspose::Slides::IGraphicalObjectLock
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准 NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准 NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | 确定在调整大小时形状是否必须保持纵横比。读取 **bool**。 |
| **bool** [get_DrilldownLocked](./get_drilldownlocked/)() override | 确定是否禁止选择此对象的子形状。读取 **bool**。 |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | 确定是否禁止将此形状添加到组中。读取 **bool**。 |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | 若所有锁定标志均已禁用则返回 true。只读 **bool**。 |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | 确定是否禁止移动此形状。读取 **bool**。 |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | 确定是否禁止选择此形状。读取 **bool**。 |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | 确定是否禁止调整此形状的大小。读取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。等价于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。等价于 C# 的 `is` 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价实现。支持自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减小指定值。 |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | 确定在调整大小时形状是否必须保持纵横比。写入 **bool**。 |
| void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) override | 确定是否禁止选择此对象的子形状。写入 **bool**。 |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | 确定是否禁止将此形状添加到组中。写入 **bool**。 |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | 确定是否禁止移动此形状。写入 **bool**。 |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | 确定是否禁止选择此形状。写入 **bool**。 |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | 确定是否禁止调整此形状的大小。写入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价实现。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [BaseShapeLock](../baseshapelock/)
* 类 [IGraphicalObjectLock](../igraphicalobjectlock/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)