---
title: Region
second_title: Aspose.Slides for C++ API 参考
description: "表示图形形状的内部。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 261
url: /zh/system.drawing/region/
---
## Region 类

表示图形形状的内部。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class Region : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | 返回当前对象的副本。 |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | 用指定矩形定义的、且不与此区域相交的那部分区域替换当前对象所表示的区域。 |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | 用指定矩形定义的、且不与此区域相交的那部分区域替换当前对象所表示的区域。 |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 用指定路径定义的、且不与此区域相交的那部分区域替换当前对象所表示的区域。 |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 用指定区域的、且不与此区域相交的那部分区域替换当前对象所表示的区域。 |
| void [Dispose](./dispose/)() | 释放当前对象获取的所有操作系统资源。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 确定指定区域在指定绘图表面上是否与当前对象所表示的区域完全相同。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管依据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管依据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | 用从当前对象中排除指定矩形定义的区域后的结果，替换当前对象所表示的区域。 |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | 用从当前对象中排除指定矩形定义的区域后的结果，替换当前对象所表示的区域。 |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 用从当前对象中排除指定路径定义的区域后的结果，替换当前对象所表示的区域。 |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 用从当前对象中排除指定区域后的结果，替换当前对象所表示的区域。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 获取一个 [RectangleF](../rectanglef/) 结构，表示在 [Graphics](../graphics/) 对象的绘图表面上界定此 [Region](./) 的矩形。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持对自定义对象进行散列。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | 返回一个 RegionData 对象，其中包含定义当前对象所表示区域的数据。 |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | 返回一个 [RectangleF](../rectanglef/) 结构数组，在应用指定矩阵变换后近似此 [Region](./)。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | 用此区域与指定矩形定义的区域的交集结果，替换当前对象所表示的区域。 |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | 用此区域与指定矩形定义的区域的交集结果，替换当前对象所表示的区域。 |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 用此区域与指定路径定义的区域的交集结果，替换当前对象所表示的区域。 |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 用此区域与指定区域的交集结果，替换当前对象所表示的区域。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 确定当前对象所表示的区域在指定绘图表面上是否具有空的内部。 |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 确定当前对象所表示的区域在指定绘图表面上是否具有无限的内部。 |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | 确定指定点是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | 确定指定点是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | 确定指定矩形的任意部分是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | 确定指定矩形的任意部分是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 使用指定的图形，确定指定点是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 使用指定的图形，确定指定点是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 使用指定的图形，确定指定矩形的任意部分是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 使用指定的图形，确定指定矩形的任意部分是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | 确定指定点是否位于当前对象所表示的区域内部。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 使用指定的图形，确定指定点是否位于当前对象所表示的区域内部。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| void [MakeEmpty](./makeempty/)() | 将当前对象初始化为空的内部。 |
| void [MakeInfinite](./makeinfinite/)() | 将此区域对象初始化为无限的内部。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
|  [Region](./region/)() | 构造一个 [Region](./) 类的新实例。 |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | 构造一个 [Region](./) 类的新实例，该实例表示由指定矩形定义的区域。 |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | 构造一个 [Region](./) 类的新实例，该实例表示由指定矩形定义的区域。 |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 构造一个 [Region](./) 类的新实例，该实例表示由指定路径定义的区域。 |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | 构造一个 [Region](./) 类的新实例，该实例表示由指定 RegionData 对象定义的区域。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 使用指定的矩阵转换此区域。 |
| void [Transform](./transform/)(const SkMatrix\&) | 使用指定的矩阵转换此区域。 |
| void [Translate](./translate/)(int, int) | 按指定量移动区域的坐标。 |
| void [Translate](./translate/)(**float**, **float**) | 按指定量移动区域的坐标。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | 用此区域与指定矩形定义的区域的并集结果，替换当前对象所表示的区域。 |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | 用此区域与指定矩形定义的区域的并集结果，替换当前对象所表示的区域。 |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 用此区域与指定路径定义的区域的并集结果，替换当前对象所表示的区域。 |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 用此区域与指定区域的并集结果，替换当前对象所表示的区域。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | 用此区域与指定矩形定义的区域的非交叉部分，替换当前对象所表示的区域。 |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | 用此区域与指定矩形定义的区域的非交叉部分，替换当前对象所表示的区域。 |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 用此区域与指定路径定义的区域的非交叉部分，替换当前对象所表示的区域。 |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 用此区域与指定区域的非交叉部分，替换当前对象所表示的区域。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
| virtual  [~Region](./~region/)() | 析构函数。 |
## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)