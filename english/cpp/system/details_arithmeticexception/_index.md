---
title: Details_ArithmeticException
second_title: Aspose.Slides for C++ API Reference
description: "ArithmeticException is throw when an error occurs during execution of arithmetic, conversion of casting operations. Never create instances of this class manually. Use the ArithmeticException class instead. Never wrap the ArithmeticException class instances into System::SmartPtr."
type: docs
weight: 313
url: /cpp/system/details_arithmeticexception/
---
## Details_ArithmeticException class


ArithmeticException is throw when an error occurs during execution of arithmetic, conversion of casting operations. Never create instances of this class manually. Use the ArithmeticException class instead. Never wrap the ArithmeticException class instances into [System::SmartPtr](../smartptr/).

```cpp
class Details_ArithmeticException : public System::Details_SystemException
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compares objects using C# [Object.Equals](../object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Returns a 32-bit integer value which is a HRESULT code associated with the exception reprsented by the current object. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Returns a reference to the object representing the inner exception. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Returns the string containing the error destcription. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Returns the string containing the stack trace. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Returns the copy of Exception object representing the inner-most exception. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../object/gethashcode/) method. Enables hashing of custom objects. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Gets actual type of object. Analog of C# [System.Object.GetType()](../object/gettype/) call. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Sets HRESULT, a coded numerical value that is assigned to a specific exception. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Returns the string representation of the current object. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implements [what()](../details_exception/what/) method which is called by [ExceptionWrapper](../exceptionwrapper/) class. Despite of the fact that this class is not inherited from std::exception derived classes can use protected/private members to implement their logic. Moving this method implementation to the [ExceptionWrapper](../exceptionwrapper/) may broke that logic. |
| virtual  [~Object](../object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Details_SystemException](../details_systemexception/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)