---
title: Matrix
second_title: Aspose.Slides for C++ API Reference
description: "Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 118
url: /cpp/system.drawing.drawing2d/matrix/
---
## Matrix class


Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Creates a copy of the current object. |
| void [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Tests whether the specified object is a [Matrix](./) and is identical to this object. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Returns an arry containing the elements of the matrix in the following order: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Determines if the matrix represented by the current object is an identity matrix. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Determines if the matrix represented by the current object is invertible. |
| **float** [get_OffsetX](./get_offsetx/)() const | Returns the X translation value of the matrix represented by the current object. |
| **float** [get_OffsetY](./get_offsety/)() const | Returns the Y translation value of the matrix represented by the current object. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| void [Invert](./invert/)() | Inverts the matrix represented by the current object. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
|  [Matrix](./matrix/)() | Constructs a new instance of [Matrix](./) class that represents an identity matrix. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Constructs a new instance of [Matrix](./) class and initializes it with the specified values. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Constructs a new instance of the [Matrix](./) class to the geometric transform defined by the specified rectangle and array of points. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Constructs a new instance of the [Matrix](./) class to the geometric transform defined by the specified rectangle and array of points. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Multiplies the matrix represented by the current object by the specified matrix. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Multiplies the matrix represented by the current object by the specified matrix. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [Reset](./reset/)() | Resets the matrix represented by the current object so that it becomes an identity matrix. |
| void [Rotate](./rotate/)(**float**) | Rotates the matrix represented by the current object clockwise by the specified angle. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Rotates the matrix represented by the current object clockwise around the origin by the specified angle. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Rotates the matrix represented by the current object clockwise around the specified point by the specified angle. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Rotates the matrix represented by the current object clockwise around the specified point by the specified angle. |
| void [Scale](./scale/)(**float**, **float**) | Applies the specified scale vector to the matrix represented by the current object. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applies the specified scale vector to the matrix represented by the current object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Applies the specified shear vector to the matrix represented by the current object. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applies the specified shear vector to the matrix represented by the current object. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| void [Translate](./translate/)(**float**, **float**) | Applies the specified translate vector to the matrix represented by the current object. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applies the specified translate vector to the matrix represented by the current object. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Multiplies each vector in an array by the matrix represented by the current object. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Multiplies each vector in an array by the matrix represented by the current object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)