---
title: Hyperlink
second_title: Aspose.Slides for C++ API Reference
description: Represents a hyperlink.
type: docs
weight: 1171
url: /aspose.slides/hyperlink/
---
## Hyperlink class


Represents a hyperlink.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determines whether the two [Hyperlink](./) instances are equal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | Returns type of [Hyperlink](./)'s action. Read-only [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | Represents the source of hyperlink color - either styles or portion format. Read [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | Returns a hyperlink which ends the show. Read-only [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | Specifies the external URL. Read-only [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | Returns a hyperlink to the first slide of the presentation. Read-only [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | Determines whether the hyperlink should be highlighted on click. Read **bool**. |
| **bool** [get_History](./get_history/)() override | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | Returns a hyperlink to the last slide of the presentation. Read-only [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | Returns a hyperlink to the last viewed slide. Read-only [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | Returns a special \"play mediafile\" hyperlink. Used in [AudioFrame](../audioframe/) and [VideoFrame](../videoframe/). Read-only [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | Returns a hyperlink to the next slide. Read-only [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | Returns a special \"do nothing\" hyperlink. Read-only [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../ipresentationcomponent/). Read-only [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | Returns a hyperlink to the previous slide. Read-only [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | Represents the playing sound of the hyperlink. Read [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | Determines whether the sound should be stopped on hyperlink click. Read **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | If the [Hyperlink](./) targets specific slide returns this slide. Read-only [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | Creates an instance of a hyperlink. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |
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
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | Represents the source of hyperlink color - either styles or portion format. Write [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | Determines whether the hyperlink should be highlighted on click. Write **bool**. |
| void [set_History](./set_history/)(**bool**) override | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Write **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Represents the playing sound of the hyperlink. Write [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | Determines whether the sound should be stopped on hyperlink click. Write **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Write [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [PVIObject](../pviobject/)
* Class [IHyperlink](../ihyperlink/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)