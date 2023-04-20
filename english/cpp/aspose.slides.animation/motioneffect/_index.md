---
title: MotionEffect
second_title: Aspose.Slides for C++ API Reference
description: Represent motion effect behavior of effect.
type: docs
weight: 469
url: /cpp/aspose.slides.animation/motioneffect/
---
## MotionEffect class


Represent motion effect behavior of effect.

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
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
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Represents whether animation behaviors are accumulated. Read [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Represents whether the current animation behavior is combined with other running animations. Read [BehaviorAdditiveType](../behavioradditivetype/). |
| **float** [get_Angle](./get_angle/)() override | Describes the relative angle of the motion path. Read **float**. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | Describes the relative offset value for the animation (in percents). Read [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | Specifies an x/y co-ordinate to start the animation from (in percents). Read [System::Drawing::PointF](../../system.drawing/pointf/). |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. Read [MotionOriginType](../motionorigintype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | Specifies the path primitive followed by coordinates for the animation motion. Read [IMotionPath](../imotionpath/). |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | Specifies how the motion path moves when shape is moved. Read [MotionPathEditMode](../motionpatheditmode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Represents properties of behavior. Read-only [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | Describes the center of the rotation used to rotate a motion path by X angle. Read [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Represents timing properties for the effect behavior. Read [ITiming](../itiming/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | Specifies the target location for an animation motion effect (in percents). Read [System::Drawing::PointF](../../system.drawing/pointf/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Represents whether animation behaviors are accumulated. Write [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Represents whether the current animation behavior is combined with other running animations. Write [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_Angle](./set_angle/)(**float**) override | Describes the relative angle of the motion path. Write **float**. |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Describes the relative offset value for the animation (in percents). Write [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Specifies an x/y co-ordinate to start the animation from (in percents). Write [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. Write [MotionOriginType](../motionorigintype/). |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | Specifies the path primitive followed by coordinates for the animation motion. Write [IMotionPath](../imotionpath/). |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | Specifies how the motion path moves when shape is moved. Write [MotionPathEditMode](../motionpatheditmode/). |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Describes the center of the rotation used to rotate a motion path by X angle. Write [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Represents timing properties for the effect behavior. Write [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Specifies the target location for an animation motion effect (in percents). Write [System::Drawing::PointF](../../system.drawing/pointf/). |
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

* Class [Behavior](../behavior/)
* Class [IMotionEffect](../imotioneffect/)
* Namespace [Aspose::Slides::Animation](../)
* Library [Aspose.Slides](../../)