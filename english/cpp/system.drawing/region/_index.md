---
title: Region
second_title: Aspose.Slides for C++ API Reference
description: "Represents the interior of a graphic shape. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 261
url: /cpp/system.drawing/region/
---
## Region class


Represents the interior of a graphic shape. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Region : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Returns a copy of the current object. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Replaces the region represented by the current object with the portion of the region defined by the specified path that does not intersect with this region. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Replaces the region represented by the current object with the portion of the specified region that does not intersect with this region. |
| void [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Replaces the region represented by the current object with the result of exclusion of the region defined by the specified rectange from it. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Replaces the region represented by the current object with the result of exclusion of the region defined by the specified rectange from it. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Replaces the region represented by the current object with the result of exclusion of the region defined by the specified path from it. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Replaces the region represented by the current object with the result of exclusion of the specified region from it. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Gets a [RectangleF](../rectanglef/) structure that represents a rectangle that bounds this [Region](./) on the drawing surface of a [Graphics](../graphics/) object. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Returns a RegionData object containing data that defines the region represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Returns an array of [RectangleF](../rectanglef/) structures that approximate this [Region](./) after the specified matrix transformation is applied. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified path. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Replaces the region represented by the current object with the result of intersection of this region and the specified region. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determines wheter the region represented by the current object has empty interior on the specified drawing surface. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determines wheter the region represented by the current object has infinite interior on the specified drawing surface. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Determines if the specified point is contained within the region represented by the current object. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Determines if the specified point is contained within the region represented by the current object. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determines if the specified point is contained within the region represented by the current object using the specified graphics. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determines if the specified point is contained within the region represented by the current object using the specified graphics. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object using the specified graphics. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object using the specified graphics. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Determines if the specified point is contained within the region represented by the current object. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determines if the specified point is contained within the region represented by the current object using the specified graphics. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [MakeEmpty](./makeempty/)() | Initializes the current object to empty interior. |
| void [MakeInfinite](./makeinfinite/)() | Initializes this region object to an infinite interior. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
|  [Region](./region/)() | Constructs a new instance of [Region](./) class. |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified rectangle. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified rectangle. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified path. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified RegionData object. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transforms this region by the specified matrix. |
| void [Transform](./transform/)(const SkMatrix\&) | Transforms this region by the specified matrix. |
| void [Translate](./translate/)(int, int) | Moves the coordinates of the region by the specified amount. |
| void [Translate](./translate/)(**float**, **float**) | Moves the coordinates of the region by the specified amount. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Replaces the region represented by the current object with the result of union operation of this region and a region defined by the specified rectangle. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Replaces the region represented by the current object with the result of union of this region and a region defined by the specified rectangle. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Replaces the region represented by the current object with the result of union of this region and a region defined by the specified path. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Replaces the region represented by the current object with the result of union of this region and and the specified region. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Replaces the region represented by the current object with the portions of this region and the region defined by the specified path that do not intersect. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Replaces the region represented by the current object with the portions of this region and the specified region that do not intersect. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
| virtual  [~Region](./~region/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)