---
title: GraphicsPath
second_title: Aspose.Slides C++ API 参考
description: "表示一组相连的直线和曲线。该类的对象应仅使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 66
url: /zh/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath 类

表示一组相连的直线和曲线。该类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class GraphicsPath : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | 向当前对象表示的路径添加指定的椭圆弧。 |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | 向当前对象表示的路径添加指定的椭圆弧。 |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | 向当前对象表示的路径添加指定的椭圆弧。 |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 向当前对象表示的路径添加指定的椭圆弧。 |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 向当前对象表示的路径添加指定的三次贝塞尔曲线。 |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 向当前对象表示的路径添加指定的三次贝塞尔曲线。 |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | 向当前对象表示的路径添加指定的三次贝塞尔曲线。 |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 向当前对象表示的路径添加指定的三次贝塞尔曲线。 |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 向当前图形添加一系列相连的三次贝塞尔曲线。 |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 向当前图形添加一系列相连的三次贝塞尔曲线。 |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 向当前对象表示的路径添加指定的闭合曲线。 |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 向当前对象表示的路径添加指定的闭合曲线。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 向当前对象表示的路径添加指定的曲线。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 向当前对象表示的路径添加指定的曲线。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | 向当前对象表示的路径添加指定的曲线。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | 向当前对象表示的路径添加指定的曲线。 |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | 向当前对象表示的路径添加指定的椭圆。 |
| void [AddEllipse](./addellipse/)(int, int, int, int) | 向当前对象表示的路径添加指定的椭圆。 |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 向当前对象表示的路径添加指定的椭圆。 |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 向当前对象表示的路径添加指定的椭圆。 |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 向当前对象表示的路径添加指定的直线。 |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 向当前对象表示的路径添加指定的直线。 |
| void [AddLine](./addline/)(int, int, int, int) | 向当前对象表示的路径添加指定的直线。 |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | 向当前对象表示的路径添加指定的直线。 |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 向当前对象表示的路径添加指定的一系列相连的线段。 |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 向当前对象表示的路径添加指定的一系列相连的线段。 |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | 向当前对象表示的路径添加指定的路径。 |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | 向当前对象表示的路径添加指定的饼形轮廓。 |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | 向当前对象表示的路径添加指定的饼形轮廓。 |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 向当前对象表示的路径添加指定的饼形轮廓。 |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 向当前对象表示的路径添加指定的多边形。 |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 向当前对象表示的路径添加指定的多边形。 |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 向当前对象表示的路径添加指定的矩形。 |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 向当前对象表示的路径添加指定的矩形。 |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | 向当前对象表示的路径添加指定的一系列矩形。 |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | 向当前对象表示的路径添加指定的一系列矩形。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 向当前对象表示的路径添加一段文本。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 向当前对象表示的路径添加一段文本。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 向当前对象表示的路径添加一段文本。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 向当前对象表示的路径添加一段文本。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | 创建当前对象的副本。 |
| void [CloseAllFigures](./closeallfigures/)() | 关闭所有打开的图形并开始一个新图形。 |
| void [CloseFigure](./closefigure/)() | 关闭当前图形并开始一个新图形。 |
| void [Dispose](./dispose/)() | 释放当前对象获取的所有操作系统资源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），这里仍将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），这里仍将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| void [Flatten](./flatten/)() | 通过将路径中的每条曲线转换为一系列相连的直线来展平路径。使用的平整度值为 0.25。 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | 通过将路径中的每条曲线转换为一系列相连的直线来展平路径。使用的平整度值为 0.25。 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | 通过将路径中的每条曲线转换为一系列相连的直线来展平路径。 |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | 返回当前对象的填充模式。 |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | 返回一个 [PathData](../pathdata/) 对象，其中包含构成当前对象表示的路径的点及其类型。 |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | 返回一个数组，包含构成当前对象表示的路径的点。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | 返回一个数组，包含指示构成当前对象表示的路径的点类型的值。 |
| int [get_PointCount](./get_pointcount/)() const | 返回当前对象表示的路径中的点数。 |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | 返回一个 [RectangleF](../../system.drawing/rectanglef/) 对象，该对象表示在使用指定矩阵转换后包围当前对象表示的路径的矩形。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | 返回一个值，该值是 Detail::FigureType 值的按位组合，指示当前对象表示的路径中包含哪些类型的图形。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持对自定义对象进行哈希。 |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | 返回一个表示路径中最后一点的 [PointF](../../system.drawing/pointf/) 对象。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | 使用指定的填充模式构造 [GraphicsPath](./) 类的新实例。 |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 构造一个表示指定路径的 [GraphicsPath](./) 对象的新实例。 |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 构造一个表示指定路径的 [GraphicsPath](./) 对象的新实例。 |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# ‘is’ 运算符。 |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 指示在使用指定的 [Pen](../../system.drawing/pen/) 绘制时，指定点是否位于此 [GraphicsPath](./) 的轮廓（下方）内。未实现。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | 确定指定点是否位于当前对象表示的路径内。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 确定指定点是否位于当前对象表示的路径内。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并使子类能够拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并使子类能够拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 为字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 为字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [Reset](./reset/)() | 通过移除所有点来清空路径。 |
| void [Reverse](./reverse/)() | 反转此 [GraphicsPath](./) 的 PathPoints 数组中点的顺序。 |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | 设置当前对象的填充模式。 |
| void [SetMarkers](./setmarkers/)() | 未实现。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [StartFigure](./startfigure/)() | 开始一个新图形。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | 通过对当前对象表示的路径应用指定的变换矩阵来转换该路径。 |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 用原始路径的轮廓替换此路径。 |
|  [~GraphicsPath](./~graphicspath/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Drawing::Drawing2D](../)
* 库 [Aspose.Slides](../../)