---
title: Matrix
second_title: Aspose.Slides for C++ API 参考
description: "表示一个定义变换操作的 3x3 矩阵。此类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 118
url: /zh/system.drawing.drawing2d/matrix/
---
## 矩阵类


表示一个定义变换操作的 3x3 矩阵。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class Matrix : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | 创建当前对象的副本。 |
| void [Dispose](./dispose/)() | 释放当前对象获取的所有操作系统资源。 |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | 测试指定的对象是否为 [Matrix](./) 且与此对象相同。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | 返回一个数组，包含矩阵的元素，顺序为：m11、m12、m21、m22、dx、dy。 |
| **bool** [get_IsIdentity](./get_isidentity/)() const | 确定当前对象表示的矩阵是否为单位矩阵。 |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | 确定当前对象表示的矩阵是否可逆。 |
| **float** [get_OffsetX](./get_offsetx/)() const | 返回当前对象表示的矩阵的 X 平移值。 |
| **float** [get_OffsetY](./get_offsety/)() const | 返回当前对象表示的矩阵的 Y 平移值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。用于对自定义对象进行哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| void [Invert](./invert/)() | 对当前对象表示的矩阵进行求逆。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [Matrix](./matrix/)() | 构造一个表示单位矩阵的 [Matrix](./) 类的新实例。 |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | 构造一个 [Matrix](./) 类的新实例，并使用指定的值进行初始化。 |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 构造一个 [Matrix](./) 类的新实例，以指定的矩形和点数组定义的几何变换。 |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 构造一个 [Matrix](./) 类的新实例，以指定的矩形和点数组定义的几何变换。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。用于克隆自定义类型。 |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | 将当前对象表示的矩阵与指定矩阵相乘。 |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | 将当前对象表示的矩阵与指定矩阵相乘。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数按指定值递减。 |
| void [Reset](./reset/)() | 重置当前对象表示的矩阵，使其成为单位矩阵。 |
| void [Rotate](./rotate/)(**float**) | 按指定角度顺时针旋转当前对象表示的矩阵。 |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | 围绕原点按指定角度顺时针旋转当前对象表示的矩阵。 |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | 围绕指定点按指定角度顺时针旋转当前对象表示的矩阵。 |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | 围绕指定点按指定角度顺时针旋转当前对象表示的矩阵。 |
| void [Scale](./scale/)(**float**, **float**) | 将指定的缩放向量应用到当前对象表示的矩阵。 |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 将指定的缩放向量应用到当前对象表示的矩阵。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Shear](./shear/)(**float**, **float**) | 将指定的剪切向量应用到当前对象表示的矩阵。 |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 将指定的剪切向量应用到当前对象表示的矩阵。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。用于将自定义对象转换为字符串。 |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 将当前对象表示的矩阵定义的几何变换应用于指定的点。 |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 将当前对象表示的矩阵定义的几何变换应用于指定的点。 |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 将当前对象表示的矩阵定义的几何变换应用于指定的点。 |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | 将当前对象表示的矩阵定义的几何变换应用于指定的点。 |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 仅将当前对象表示的矩阵的缩放和旋转分量应用于指定的点。 |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 仅将当前对象表示的矩阵的缩放和旋转分量应用于指定的点。 |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 仅将当前对象表示的矩阵的缩放和旋转分量应用于指定的点。 |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | 仅将当前对象表示的矩阵的缩放和旋转分量应用于指定的点。 |
| void [Translate](./translate/)(**float**, **float**) | 将指定的平移向量应用到当前对象表示的矩阵。 |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 将指定的平移向量应用到当前对象表示的矩阵。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 将数组中的每个向量乘以当前对象表示的矩阵。 |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 将数组中的每个向量乘以当前对象表示的矩阵。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Matrix](./~matrix/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [Object](../../system/object/)
* 命名空间 [System::Drawing::Drawing2D](../)
* 库 [Aspose.Slides](../../)