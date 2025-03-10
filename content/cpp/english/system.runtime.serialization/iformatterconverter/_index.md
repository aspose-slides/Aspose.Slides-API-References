---
title: IFormatterConverter
second_title: Aspose.Slides for C++ API Reference
description: "Provides the connection between an instance of System::Runtime::Serialization::SerializationInfo and the formatter-provided class best suited to parse the data inside the System::Runtime::Serialization::SerializationInfo."
type: docs
weight: 27
url: /system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter class


Provides the connection between an instance of [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) and the formatter-provided class best suited to parse the data inside the [System::Runtime::Serialization::SerializationInfo](../serializationinfo/).

```cpp
class IFormatterConverter : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) | RTTI information. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [TypeCode](../../system/typecode/)) | Converts a value to the given [System::TypeCode](../../system/typecode/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
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
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a bool. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **uint8_t**. |
| virtual char16_t [ToChar](./tochar/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a char16_t. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a [Decimal](../../system/decimal/). |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a double. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **int16_t**. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **int32_t**. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **int64_t**. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **int8_t**. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a float. |
| virtual [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **uint16_t**. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **uint32_t**. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Converts a value to a **uint64_t**. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.Slides](../../)