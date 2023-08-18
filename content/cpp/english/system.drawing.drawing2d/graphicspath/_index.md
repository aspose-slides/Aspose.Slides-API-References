---
title: GraphicsPath
second_title: Aspose.Slides for C++ API Reference
description: "Represents a set of connected lines and curves. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 66
url: /system.drawing.drawing2d/graphicspath/
---
## GraphicsPath class


Represents a set of connected lines and curves. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GraphicsPath : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Adds the specified elliptical arc to the path represented by the current object. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Adds the specified elliptical arc to the path represented by the current object. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Adds the specified elliptical arc to the path represented by the current object. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Adds the specified elliptical arc to the path represented by the current object. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Adds a sequence of connected cubic Bezier curves to the current figure. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Adds a sequence of connected cubic Bezier curves to the current figure. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Adds the specified closed curve to the path represented by the current object. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Adds the specified closed curve to the path represented by the current object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Adds the specified curve to the path represented by the current object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Adds the specified curve to the path represented by the current object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Adds the specified curve to the path represented by the current object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Adds the specified curve to the path represented by the current object. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Adds the specified ellipse to the path represented by the current object. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Adds the specified ellipse to the path represented by the current object. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Adds the specified ellipse to the path represented by the current object. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Adds the specified ellipse to the path represented by the current object. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Adds the specified line to the path represented by the current object. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Adds the specified line to the path represented by the current object. |
| void [AddLine](./addline/)(int, int, int, int) | Adds the specified line to the path represented by the current object. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Adds the specified line to the path represented by the current object. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Adds the specified series of connected line segments to the path represented by the current object. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Adds the specified series of connected line segments to the path represented by the current object. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Adds the specified path to the path represented by the current object. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Adds the specified outline of the pie shape to the path represented by the current object. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Adds the specified outline of the pie shape to the path represented by the current object. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Adds the specified outline of the pie shape to the path represented by the current object. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Adds the specified polygon to the path represented by the current object. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Adds the specified polygon to the path represented by the current object. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Adds the specified rectangle to the path represented by the current object. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Adds the specified rectangle to the path represented by the current object. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Adds the specified series of rectangles to the path represented by the current object. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Adds the specified series of rectangles to the path represented by the current object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adds a string of text to the path represented by the current object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adds a string of text to the path represented by the current object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adds a string of text to the path represented by the current object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adds a string of text to the path represented by the current object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Creates a copy of the current object. |
| void [CloseAllFigures](./closeallfigures/)() | Closes all open figures and starts a new one. |
| void [CloseFigure](./closefigure/)() | Closes the current figure and starts a new one. |
| void [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| void [Flatten](./flatten/)() | Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Flattens each curve in the path by converting them into a series of connected lines. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Returns the fill mode of the current object. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Returns a [PathData](../pathdata/) object containing the points that make up a path represented by the current object and their types. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Returns an array that contains points that make up a path represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Returns an array that contains values that indicate the types of the points that make up a path represented by the current object. |
| int [get_PointCount](./get_pointcount/)() const | Returns the number of points in the path represented by the current object. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Returns a [RectangleF](../../system.drawing/rectanglef/) object that represents a rectangle that bounds the path represented by the current object when it is transformed with the specified matrix. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Returns a value which is a bitwise combination of Detail::FigureType values that indicates what types of figures are contained within the path represented by the current object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Returns a [PointF](../../system.drawing/pointf/) object representing the last point in the path. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Constructs a new instance of [GraphicsPath](./) class with the specified fill mode. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Constructs a new instance of [GraphicsPath](./) object that represents the specified path. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Constructs a new instance of [GraphicsPath](./) object that represents the specified path. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](./) when drawn with the specified [Pen](../../system.drawing/pen/). NOT EMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Determines if the specified point is contained within the path represented by the current object. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Determines if the specified point is contained within the path represented by the current object. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [Reset](./reset/)() | Empties the path by removing all points from it. |
| void [Reverse](./reverse/)() | Reverses the order of points in the PathPoints array of this [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Sets the fill mode of the current object. |
| void [SetMarkers](./setmarkers/)() | NOT IMPLEMENTED. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [StartFigure](./startfigure/)() | Starts a new figure. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transforms the path represented by the current object by applying the specified transform matrix to it. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Replaces this path with an outline around the original path. |
|  [~GraphicsPath](./~graphicspath/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)