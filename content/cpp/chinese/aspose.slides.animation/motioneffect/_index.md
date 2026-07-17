---
title: MotionEffect
second_title: Aspose.Slides C++ API 参考
description: 表示效果的运动效果行为。
type: docs
weight: 469
url: /zh/aspose.slides.animation/motioneffect/
---
## MotionEffect 类

表示效果的运动效果行为。

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | 表示动画行为是否被累积。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | 表示当前动画行为是否与其他正在运行的动画合并。读取 [BehaviorAdditiveType](../behavioradditivetype/)。 |
| **float** [get_Angle](./get_angle/)() override | 描述运动路径的相对角度。读取 **float**。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | 描述动画的相对偏移值（以百分比表示）。读取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | 指定动画起始的 x/y 坐标（以百分比表示）。读取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | 指定运动路径的起点相对于什么，例如幻灯片布局或父对象。读取 [MotionOriginType](../motionorigintype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | 指定路径原语以及随后的坐标用于动画运动。读取 [IMotionPath](../imotionpath/)。 |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | 指定形状移动时运动路径的移动方式。读取 [MotionPathEditMode](../motionpatheditmode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | 表示行为的属性。只读 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | 描述用于将运动路径旋转 X 角度的旋转中心。读取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | 表示效果行为的计时属性。读取 [ITiming](../itiming/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | 指定动画运动效果的目标位置（以百分比表示）。读取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 守卫对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | 表示动画行为是否被累积。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | 表示当前动画行为是否与其他正在运行的动画合并。写入 [BehaviorAdditiveType](../behavioradditivetype/)。 |
| void [set_Angle](./set_angle/)(**float**) override | 描述运动路径的相对角度。写入 **float**。 |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 描述动画的相对偏移值（以百分比表示）。写入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 指定动画起始的 x/y 坐标（以百分比表示）。写入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | 指定运动路径相对于什么（如幻灯片布局或父对象）的起点。写入 [MotionOriginType](../motionorigintype/)。 |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | 指定路径原语以及随后的坐标用于动画运动。写入 [IMotionPath](../imotionpath/)。 |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | 指定形状移动时运动路径的移动方式。写入 [MotionPathEditMode](../motionpatheditmode/)。 |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 描述用于将运动路径旋转 X 角度的旋转中心。写入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | 表示效果行为的计时属性。写入 [ITiming](../itiming/)。 |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 指定动画运动效果的目标位置（以百分比表示）。写入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 守卫对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Behavior](../behavior/)
* 类 [IMotionEffect](../imotioneffect/)
* 命名空间 [Aspose::Slides::Animation](../)
* 库 [Aspose.Slides](../../)