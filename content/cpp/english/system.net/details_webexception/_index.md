---
title: Details_WebException
second_title: Aspose.Slides for C++ API Reference
description: "Represents the exception that is thrown by WebRequest when an error occurs. Never create instances of this class manually. Use the WebException class instead. Never wrap the WebException class instances into System::SmartPtr."
type: docs
weight: 92
url: /system.net/details_webexception/
---
## Details_WebException class


Represents the exception that is thrown by [WebRequest](../webrequest/) when an error occurs. Never create instances of this class manually. Use the WebException class instead. Never wrap the WebException class instances into [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_WebException : public System::Details_InvalidOperationException
```

## Methods

| Method | Description |
| --- | --- |
| static [Exception](../../system/exception/) [CreateCompatibleException](./createcompatibleexception/)([Exception](../../system/exception/)) | Is not implemented. |
|  [Details_WebException](./details_webexception/)() | Constructs a new instance. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/)) | Constructs a new instance. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Constructs a new instance. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [WebExceptionStatus](../webexceptionstatus/)) | Constructs a new instance. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/), [WebExceptionStatus](../webexceptionstatus/), [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\>) | Constructs a new instance. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Returns a 32-bit integer value which is a HRESULT code associated with the exception reprsented by the current object. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Returns a reference to the object representing the inner exception. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Returns the string containing the error destcription. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [get_Response](./get_response/)() | Returns the web response with which the current exception is associated. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Returns the string containing the stack trace. |
| [WebExceptionStatus](../webexceptionstatus/) [get_Status](./get_status/)() | Returns the status code. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Returns the copy of Exception object representing the inner-most exception. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
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
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Sets HRESULT, a coded numerical value that is assigned to a specific exception. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Returns the string representation of the current object. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implements [what()](../../system/details_exception/what/) method which is called by [ExceptionWrapper](../../system/exceptionwrapper/) class. Despite of the fact that this class is not inherited from std::exception derived classes can use protected/private members to implement their logic. Moving this method implementation to the [ExceptionWrapper](../../system/exceptionwrapper/) may broke that logic. |
| virtual  [~Details_WebException](./~details_webexception/)() | Destructs the current instance. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)