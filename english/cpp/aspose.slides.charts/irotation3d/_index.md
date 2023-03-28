---
title: IRotation3D
second_title: Aspose.Slides for C++ API Reference
description: Represents 3D rotation of a chart.
type: docs
weight: 1171
url: /cpp/aspose.slides.charts/irotation3d/
---
## IRotation3D class


Represents 3D rotation of a chart.

```cpp
class IRotation3D : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Returns the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). Read **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). Read **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Returns the perspective value (field of view angle) for 3D charts (between 0 and 100). Ignored if RightAngleAxes property value is true. Read **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Determines whether the chart axes are at right angles, rather than drawn in perspective. In other words it determines whether the chart angles of axes are independent from chart rotation or elevation. Read **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Returns the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the \"Y Rotation\" option in PowerPoint 2007+. Read **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Returns the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the \"X Rotation\" option in PowerPoint 2007+. Read **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
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
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). Write **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). Write **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Sets the perspective value (field of view angle) for 3D charts (between 0 and 100). Ignored if RightAngleAxes property value is true. Write **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Determines whether the chart axes are at right angles, rather than drawn in perspective. In other words it determines whether the chart angles of axes are independent from chart rotation or elevation. Write **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the \"Y Rotation\" option in PowerPoint 2007+. Write **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the \"X Rotation\" option in PowerPoint 2007+. Write **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)
