---
title: SlideShowSettings
second_title: Aspose.Slides for C++ API Reference
description: Represents the slide show settings for the presentation.
type: docs
weight: 4954
url: /aspose.slides/slideshowsettings/
---
## SlideShowSettings class


Represents the slide show settings for the presentation.

```cpp
class SlideShowSettings : public System::Object
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
| **bool** [get_Loop](./get_loop/)() | Loop [Slide](../slide/) Show |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_PenColor](./get_pencolor/)() | Pen Color for [Slide](../slide/) Show |
| **bool** [get_ShowAnimation](./get_showanimation/)() | Show [Animation](../../aspose.slides.animation/) in [Slide](../slide/) Show |
| **bool** [get_ShowMediaControls](./get_showmediacontrols/)() const | Show Media Controls |
| **bool** [get_ShowNarration](./get_shownarration/)() | Show Narration in [Slide](../slide/) Show |
| [System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\> [get_Slides](./get_slides/)() const | [Slides](../) range |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\> [get_SlideShowType](./get_slideshowtype/)() | Gets the slide show type. Represented by the following [SlideShowType](../slideshowtype/) ancestors: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) and [BrowsedByIndividual](../browsedbyindividual/) |
| **bool** [get_UseTimings](./get_usetimings/)() | Use Timings in [Slide](../slide/) Show |
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
| void [set_Loop](./set_loop/)(**bool**) | Loop [Slide](../slide/) Show |
| void [set_ShowAnimation](./set_showanimation/)(**bool**) | Show [Animation](../../aspose.slides.animation/) in [Slide](../slide/) Show |
| void [set_ShowMediaControls](./set_showmediacontrols/)(**bool**) | Show Media Controls |
| void [set_ShowNarration](./set_shownarration/)(**bool**) | Show Narration in [Slide](../slide/) Show |
| void [set_Slides](./set_slides/)([System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\>) | [Slides](../) range |
| void [set_SlideShowType](./set_slideshowtype/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\>) | Sets the slide show type. Represented by the following [SlideShowType](../slideshowtype/) ancestors: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) and [BrowsedByIndividual](../browsedbyindividual/) |
| void [set_UseTimings](./set_usetimings/)(**bool**) | Use Timings in [Slide](../slide/) Show |
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
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)