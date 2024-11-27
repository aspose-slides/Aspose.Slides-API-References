---
title: IModernComment
second_title: Aspose.Slides for C++ API Reference
description: Represents a comment on a slide.
type: docs
weight: 2887
url: /aspose.slides/imoderncomment/
---
## IModernComment class


Represents a comment on a slide.

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | Returns the author of a comment. Read-only [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | Returns the time of a comment creation. Setting this property to [DateTime::MinValue](../../system/datetime/minvalue/) means no comment time is set. Read [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | Gets parent comment. Read [IComment](../icomment/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | Returns the position of a comment on a slide. Read [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | Returns a shape associated with the comment. Read-only [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | Returns the parent slide of a comment. Read-only [ISlide](../islide/). |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | Returns the status of the comment. Read [ModernCommentStatus](../moderncommentstatus/). |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | Returns the plain text of a slide comment. Read [System::String](../../system/string/). |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | Returns text selection length in text frame if the comment associated with [AutoShape](../autoshape/). Read **int32_t**. |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | Returns starting position of text selection in text frame if the comment associated with [AutoShape](../autoshape/). Read **int32_t**. |
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
| virtual void [Remove](../icomment/remove/)() | Removes comment and all its replies from the parent collection. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | Sets the time of a comment creation. Setting this property to [DateTime::MinValue](../../system/datetime/minvalue/) means no comment time is set. Write [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | Sets parent comment. Write [IComment](../icomment/). |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Sets the position of a comment on a slide. Write [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | Sets the status of the comment. Write [ModernCommentStatus](../moderncommentstatus/). |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | Sets the plain text of a slide comment. Write [System::String](../../system/string/). |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | Sets text selection length in text frame if the comment associated with [AutoShape](../autoshape/). Write **int32_t**. |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | Sets starting position of text selection in text frame if the comment associated with [AutoShape](../autoshape/). Write **int32_t**. |
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



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## See Also

* Class [IComment](../icomment/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)