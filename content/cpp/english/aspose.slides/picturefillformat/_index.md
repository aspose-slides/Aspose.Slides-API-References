---
title: PictureFillFormat
second_title: Aspose.Slides for C++ API Reference
description: Represents a picture fill style.
type: docs
weight: 4486
url: /aspose.slides/picturefillformat/
---
## PictureFillFormat class


Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Delete cropped areas of the fill [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compares with specified object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Returns the number of percents of real image height that are cropped off the bottom of the picture. Read **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Returns the number of percents of real image width that are cropped off the left of the picture. Read **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Returns the number of percents of real image width that are cropped off the right of the picture. Read **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Returns the number of percents of real image height that are cropped off the top of the picture. Read **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Returns the dpi which is used to fill a picture. Read **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returns Parent_Immediate object. Read-only [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../ipresentationcomponent/). Read-only [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Returns the picture. Read-only [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Returns the picture fill mode. Read [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Returns bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Returns left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Returns right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Returns top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returns hash code. |
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
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Sets the number of percents of real image height that are cropped off the bottom of the picture. Write **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Sets the number of percents of real image width that are cropped off the left of the picture. Write **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Sets the number of percents of real image width that are cropped off the right of the picture. Write **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Sets the number of percents of real image height that are cropped off the top of the picture. Write **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Sets the dpi which is used to fill a picture. Write **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Sets the picture fill mode. Write [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Write **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Write **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Write **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Write **float**. |
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
* Class [IPictureFillFormat](../ipicturefillformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)