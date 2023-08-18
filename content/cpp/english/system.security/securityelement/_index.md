---
title: SecurityElement
second_title: Aspose.Slides for C++ API Reference
description: "XML object model for encoding security object. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 40
url: /system.security/securityelement/
---
## SecurityElement class


XML object model for encoding security object. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SecurityElement : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Adds attribute to tag. |
| void [AddChild](./addchild/)([SecurityElement](./)) | Adds child tag. |
| [String](../../system/string/) [Attribute](./attribute/)(const [String](../../system/string/)\&) | Gets attribute value. |
| [SecurityElement](./) [Copy](./copy/)() | Clones tag. |
| **bool** [Equal](./equal/)([SecurityElement](./)) | Checks for parameters equality. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Escapes characters in XML string. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| static [SecurityElement](./) [FromString](./fromstring/)(const [String](../../system/string/)\&) | Creates element from XML code. |
| [System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\> [get_Attributes](./get_attributes/)() | Gets tag attributes. |
| [System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\> [get_Children](./get_children/)() | Gets tag child objects. |
| [String](../../system/string/) [get_Tag](./get_tag/)() | Gets tag name. |
| [String](../../system/string/) [get_Text](./get_text/)() | Gets tag inner text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsValidAttributeName](./isvalidattributename/)(const [String](../../system/string/)\&) | Checks if attribute name is valid. |
| static **bool** [IsValidAttributeValue](./isvalidattributevalue/)(const [String](../../system/string/)\&) | Checks if attribute value is valid. |
| static **bool** [IsValidTag](./isvalidtag/)(const [String](../../system/string/)\&) | Checks if tag is valid. |
| static **bool** [IsValidText](./isvalidtext/)(const [String](../../system/string/)\&) | Checks if text is valid. |
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
| [SecurityElement](./) [SearchForChildByTag](./searchforchildbytag/)(const [String](../../system/string/)\&) | Gets child tag by name. |
| [String](../../system/string/) [SearchForTextOfTag](./searchfortextoftag/)(const [String](../../system/string/)\&) | Gets child tag inner text by tag name. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&) | Constructor. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
| void [set_Attributes](./set_attributes/)([System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>) | Sets tag attributes. |
| void [set_Children](./set_children/)([System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\>) | Sets tag child objects. |
| void [set_Tag](./set_tag/)(const [String](../../system/string/)\&) | Sets tag name. |
| void [set_Text](./set_text/)(const [String](../../system/string/)\&) | Sets tag inner text. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Converts tag to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.Slides](../../)