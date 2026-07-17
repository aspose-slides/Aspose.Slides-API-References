---
title: IConnectorLock
second_title: Aspose.Slides C++ API 参考
description: 确定在父 Connector 上禁用的操作。
type: docs
weight: 1860
url: /zh/aspose.slides/iconnectorlock/
---
## IConnectorLock 类

确定在父 [Connector](../connector/) 上禁用的操作。

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），这里两个 NaN 被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），这里两个 NaN 被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | 确定是否禁止更改调整值。只读 **bool**。 |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | 确定是否禁止更改箭头。只读 **bool**。 |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | 确定在调整大小时形状是否必须保持纵横比。只读 **bool**。 |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | 确定是否禁止直接更改此形状的轮廓。只读 **bool**。 |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | 确定是否禁止将此形状添加到组中。只读 **bool**。 |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | 如果所有锁标志均已禁用则返回 true。只读 **bool**。 |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | 确定是否禁止移动此形状。只读 **bool**。 |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | 确定是否禁止更改此形状的旋转角度。只读 **bool**。 |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | 确定是否禁止选择此形状。只读 **bool**。 |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | 确定是否禁止更改形状类型。只读 **bool**。 |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | 确定是否禁止调整此形状的大小。只读 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用对自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为目标类型（targetType）描述的实例。相当于 C# 'is' 操作符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | 确定是否禁止更改调整值。写入 **bool**。 |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | 确定是否禁止更改箭头。写入 **bool**。 |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | 确定在调整大小时形状是否必须保持纵横比。写入 **bool**。 |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | 确定是否禁止直接更改此形状的轮廓。写入 **bool**。 |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | 确定是否禁止将此形状添加到组中。写入 **bool**。 |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | 确定是否禁止移动此形状。写入 **bool**。 |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | 确定是否禁止更改此形状的旋转角度。写入 **bool**。 |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | 确定是否禁止选择此形状。写入 **bool**。 |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | 确定是否禁止更改形状类型。写入 **bool**。 |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | 确定是否禁止调整此形状的大小。写入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IBaseShapeLock](../ibaseshapelock/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)