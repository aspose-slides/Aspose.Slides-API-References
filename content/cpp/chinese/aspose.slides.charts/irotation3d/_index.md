---
title: IRotation3D
second_title: Aspose.Slides for C++ API 参考
description: 表示图表的 3D 旋转。
type: docs
weight: 1171
url: /zh/aspose.slides.charts/irotation3d/
---
## IRotation3D 类

表示图表的 3D 旋转。

```cpp
class IRotation3D : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | 返回 3D 图表的深度，以图表宽度的百分比表示（介于 20% 到 2000% 之间）。读取 **uint16_t**。 |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | 指定 3D 图表的高度，以图表宽度的百分比表示（介于 5% 到 500% 之间）。读取 **uint16_t**。 |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | 返回 3D 图表的透视值（视场角），范围为 0 到 100。如果 RightAngleAxes 属性为 true，则忽略。读取 **uint8_t**。 |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | 确定图表坐标轴是否为直角，而非透视绘制。换句话说，它决定坐标轴的角度是否独立于图表的旋转或倾斜。读取 **bool**。 |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | 返回围绕 X 轴（即 3D 图表的 Y 方向）的旋转角度（范围为 -90 到 90 度）。该属性对应 ECMA-376 中的 21.2.2.157 rotX（X 旋转）项以及 PowerPoint 2007+ 中的 “Y Rotation” 选项。读取 **int8_t**。 |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | 返回围绕 Y 轴（即 3D 图表的 X 方向）的旋转角度（范围为 0 到 360 度）。该属性对应 ECMA-376 中的 21.2.2.158 rotY（Y 旋转）项以及 PowerPoint 2007+ 中的 “X Rotation” 选项。读取 **uint16_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | 设置 3D 图表的深度，以图表宽度的百分比表示（介于 20% 到 2000% 之间）。写入 **uint16_t**。 |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | 指定 3D 图表的高度，以图表宽度的百分比表示（介于 5% 到 500% 之间）。写入 **uint16_t**。 |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | 设置 3D 图表的透视值（视场角），范围为 0 到 100。如果 RightAngleAxes 属性为 true，则忽略。写入 **uint8_t**。 |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | 确定图表坐标轴是否为直角，而非透视绘制。换句话说，它决定坐标轴的角度是否独立于图表的旋转或倾斜。写入 **bool**。 |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | 设置围绕 X 轴（即 3D 图表的 Y 方向）的旋转角度（范围为 -90 到 90 度）。该属性对应 ECMA-376 中的 21.2.2.157 rotX（X 旋转）项以及 PowerPoint 2007+ 中的 “Y Rotation” 选项。写入 **int8_t**。 |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | 设置围绕 Y 轴（即 3D 图表的 X 方向）的旋转角度（范围为 0 到 360 度）。该属性对应 ECMA-376 中的 21.2.2.158 rotY（Y 旋转）项以及 PowerPoint 2007+ 中的 “X Rotation” 选项。写入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
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

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)