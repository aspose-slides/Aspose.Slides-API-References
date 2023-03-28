---
title: Cookie
second_title: Aspose.Slides for C++ API Reference
description: "Represents an HTTP cookie. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 1
url: /cpp/system.net/cookie/
---
## Cookie class


Represents an HTTP cookie. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Cookie : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Creates a copy of the current instance. |
|  [Cookie](./cookie/)() | Constructs a new instance. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Constructs a new instance. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Constructs a new instance. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Constructs a new instance. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Gets the 'Comment' attribute's value. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Gets the 'CommentURL' attribute's value. |
| **bool** [get_Discard](./get_discard/)() const | Gets the 'Discard' attribute's value. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Gets the 'Domain' attribute's value. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Gets a value that indicates if the domain is implicit. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Returns the domain key. |
| **bool** [get_Expired](./get_expired/)() | Gets a value that indicates if the cookie expired. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Gets the 'Expires' attribute's value. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Gets the 'HttpOnly' attribute's value. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Gets the cookie's name. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Gets the 'Path' attribute's value. |
| **bool** [get_Plain](./get_plain/)() const | Returns a value that indicates if the cookie specification is 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Gets the 'Port' attribute's value. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Returns the collection of the 'Port' attribute's values. |
| **bool** [get_Secure](./get_secure/)() const | Gets the 'Secure' attribute's value. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Returns the time when the cookie was created. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Gets the cookie's'value. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Gets the cookie's specification. |
| **int32_t** [get_Version](./get_version/)() const | Gets the '[Version](../../system/version/)' attribute's value. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | This method is called by other methods to set a method name. |
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
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Sets the 'Comment' attribute's value. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Sets the 'CommentURL' attribute's value. |
| void [set_Discard](./set_discard/)(**bool**) | Sets the 'Discard' attribute's value. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Sets the 'Domain' attribute's value. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Sets a value that indicates if the domain is implicit. |
| void [set_Expired](./set_expired/)(**bool**) | Sets a value that indicates if the cookie expired. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Sets the 'Expires' attribute's value. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Sets the 'HttpOnly' attribute's value. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Sets the cookie's name. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Sets the 'Path' attribute's value. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Sets the 'Port' attribute's value. |
| void [set_Secure](./set_secure/)(**bool**) | Sets the 'Secure' attribute's value. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Sets the cookie's value. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Sets the cookie's specification. |
| void [set_Version](./set_version/)(**int32_t**) | Sets the '[Version](../../system/version/)' attribute's value. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serializes the current instance to the string representation. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifies and sets the default attribute's values. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Fields

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | The 'Comment' attribute's name. |
| static [CommentUrlAttributeName](./commenturlattributename/) | The 'CommentURL' attribute's name. |
| static [DiscardAttributeName](./discardattributename/) | The 'Discard' attribute's name. |
| static [DomainAttributeName](./domainattributename/) | The 'Domain' attribute's name. |
| static [EqualsLiteral](./equalsliteral/) | The separator that is used to separates the name and value of an attribute. |
| static [ExpiresAttributeName](./expiresattributename/) | The 'Expires' attribute's name. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | The 'HttpOnly' attribute's name. |
| static [MaxAgeAttributeName](./maxageattributename/) | The 'Max-Age' attribute's name. |
| static [MaxSupportedVersion](./maxsupportedversion/) | The maximum supported version. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | The string representation of the maximum supported version. |
| static [PathAttributeName](./pathattributename/) | The 'Path' attribute's name. |
| static [PortAttributeName](./portattributename/) | The 'Port' attribute's name. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | The array that contains delimiters for the 'Port' attribute's values. |
| static [QuotesLiteral](./quotesliteral/) | The symbol used to wrap the attribute's parts. |
| static [ReservedToName](./reservedtoname/) | A value that is reserved for the cookie name. |
| static [ReservedToValue](./reservedtovalue/) | A value that is reserved for the cookie value. |
| static [SecureAttributeName](./secureattributename/) | The 'Secure' attribute's name. |
| static [SeparatorLiteral](./separatorliteral/) | The attribute separator. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | The prefix of the special attributes' names. |
| static [VersionAttributeName](./versionattributename/) | The '[Version](../../system/version/)' attribute's name. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)
