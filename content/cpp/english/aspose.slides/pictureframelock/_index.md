---
title: PictureFrameLock
second_title: Aspose.Slides for C++ API Reference
description: Determines which operations are disabled on the parent PictureFrame.
type: docs
weight: 4720
url: /aspose.slides/pictureframelock/
---
## PictureFrameLock class


Determines which operations are disabled on the parent [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
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
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Determines whether a changing adjust values is forbidden. Read **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Determines whether a changing arrowheads is forbidden. Read **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Determines whether a shape have to preserve aspect ratio on resizing. Read **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Determines whether an image cropping is forbidden. Read **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Determines whether a direct changing of contour of this shape is forbidden. Read **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Determines whether an adding this shape to a group is forbidden. Read **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Return true if all lock-flags are disabled. Read-only **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Determines whether a moving this shape is forbidden. Read **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Determines whether a changing rotation angle of this shape is forbidden. Read **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Determines whether a selecting this shape is forbidden. Read **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Determines whether a changing of a shape type is forbidden. Read **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Determines whether a resizing this shape is forbidden. Read **bool**. |
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
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Determines whether a changing adjust values is forbidden. Write **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Determines whether a changing arrowheads is forbidden. Write **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Determines whether a shape have to preserve aspect ratio on resizing. Write **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Determines whether an image cropping is forbidden. Write **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Determines whether a direct changing of contour of this shape is forbidden. Write **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Determines whether an adding this shape to a group is forbidden. Write **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Determines whether a moving this shape is forbidden. Write **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Determines whether a changing rotation angle of this shape is forbidden. Write **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Determines whether a selecting this shape is forbidden. Write **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Determines whether a changing of a shape type is forbidden. Write **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Determines whether a resizing this shape is forbidden. Write **bool**. |
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

* Class [BaseShapeLock](../baseshapelock/)
* Class [IPictureFrameLock](../ipictureframelock/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)