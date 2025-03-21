---
title: NormalViewProperties
second_title: Aspose.Slides for C++ API Reference
description: "Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region."
type: docs
weight: 4499
url: /aspose.slides/normalviewproperties/
---
## NormalViewProperties class


Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region.

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
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
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide. |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read opnly [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read only [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read **bool**. |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read **bool**. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region. |
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
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide. |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Write **bool**. |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Write **bool**. |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Write **bool**. |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region. |
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
## Remarks


The following example shows how to configure [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/) properties of a PowerPoint [Presentation](../presentation/). 
```cpp
// Instantiate a presentation object that represents a presentation file
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## See Also

* Class [INormalViewProperties](../inormalviewproperties/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)