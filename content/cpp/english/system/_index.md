---
title: System
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 261
url: /system/
---



## Classes

| Class | Description |
| --- | --- |
| [Activator](./activator/) | Contains methods to create types of objects. |
| [Array](./array/) | Class that represents an array data structure. Objects of this class should only be allocated using [System::MakeArray()](./makearray/) and [System::MakeObject()](./makeobject/) functions. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ArraySegment](./arraysegment/) | Represents a segment of the one-dimensional array. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Attribute](./attribute/) | A base class for custom attributes. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BitConverter](./bitconverter/) | Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means. |
| [Boolean](./boolean/) | Class that keeps static members of [System.Boolean](./boolean/) .[Net](../system.net/) type. |
| [BoxedEnum](./boxedenum/) | Represents boxed enumeration value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BoxedValue](./boxedvalue/) | Represents a boxed value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BoxedValueBase](./boxedvaluebase/) | A base class that defines an interface and implements some fundamental methods of a descendant class that represents a boxed value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Buffer](./buffer/) | Contains methods that manipulate raw byte arrays. This is a static type with no instance services. You should never create instances of it by any means. |
| [Byte](./byte/) | Contains methods to work with the unsigned 8-bit integer. |
| [Char](./char/) | Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means. |
| [Comparison](./comparison/) | Represents a pointer to the method that compares two objects of the same type. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Console](./console/) | Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means. |
| [ConsoleOutput](./consoleoutput/) | Represents the standard output stream. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [DateTime](./datetime/) | Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [DateTimeOffset](./datetimeoffset/) | Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [DBNull](./dbnull/) | Represents a non-existing value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Decimal](./decimal/) | Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | Represents a pointer to a function, method or a function object. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Details_ApplicationException](./details_applicationexception/) | A base class for classes that represent application (rather than system) exceptions. Never create instances of this class manually. Use the ApplicationException class instead. Never wrap the ApplicationException class instances into [System::SmartPtr](./smartptr/). |
| [Details_ArgumentException](./details_argumentexception/) | ArgumentException is thrown when an argument passed to a method being invoked is invalid. Never create instances of this class manually. Use the ArgumentException class instead. Never wrap the ArgumentException class instances into [System::SmartPtr](./smartptr/). |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | ArgumentOutOfRangeException is thrown when a method being invoked is passed an argument that falls out of the expected range of values for that argument. Never create instances of this class manually. Use the ArgumentOutOfRangeException class instead. Never wrap the ArgumentOutOfRangeException class instances into [System::SmartPtr](./smartptr/). |
| [Details_ArithmeticException](./details_arithmeticexception/) | ArithmeticException is throw when an error occurs during execution of arithmetic, conversion of casting operations. Never create instances of this class manually. Use the ArithmeticException class instead. Never wrap the ArithmeticException class instances into [System::SmartPtr](./smartptr/). |
| [Details_BadImageFormatException](./details_badimageformatexception/) | The exception that is thrown when the file image of a dynamic link library (DLL) or an executable program is invalid. Never create instances of this class manually. Use the BadImageFormatException class instead. Never wrap the BadImageFormatException class instances into [System::SmartPtr](./smartptr/). |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | DivideByZeroException is thrown when division by 0 is attempted in an arithmetic operation. Never create instances of this class manually. Use the DivideByZeroException class instead. Never wrap the DivideByZeroException class instances into [System::SmartPtr](./smartptr/). |
| [Details_Exception](./details_exception/) | Represents an exception. Never create instances of this class manually. Use the Exception class instead. Never wrap the Exception class instances into [System::SmartPtr](./smartptr/). |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | The template class for an exception with an error code. |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | The template class for an exception with a file name. |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException is present for compatibility reasons only. |
| [Details_FormatException](./details_formatexception/) | FormatException is thrown when the format of the method's argument is not valid. Never create instances of this class manually. Use the FormatException class instead. Never wrap the FormatException class instances into [System::SmartPtr](./smartptr/). |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | IndexOutOfRangeException is thrown when an access to an element of a collection is attempted using an index that is outside its bounds. Never create instances of this class manually. Use the IndexOutOfRangeException class instead. Never wrap the IndexOutOfRangeException class instances into [System::SmartPtr](./smartptr/). |
| [Details_InvalidCastException](./details_invalidcastexception/) | InvalidCastException is thrown when invalid casting operation of invalid explicit conversion is attempted. Never create instances of this class manually. Use the InvalidCastException class instead. Never wrap the InvalidCastException class instances into [System::SmartPtr](./smartptr/). |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | The exception that is thrown when a method is invoked on an object which is in the state inconsistent with this call. Never create instances of this class manually. Use the InvalidOperationException class instead. Never wrap the InvalidOperationException class instances into [System::SmartPtr](./smartptr/). |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException is present for compatibility reasons only. Never create instances of this class manually. Use the InvalidProgramException class instead. Never wrap the InvalidProgramException class instances into [System::SmartPtr](./smartptr/). |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | InvalidTimeZoneException is thrown when time zone information is invalid. Never create instances of this class manually. Use the InvalidTimeZoneException class instead. Never wrap the InvalidTimeZoneException class instances into [System::SmartPtr](./smartptr/). |
| [Details_MemberAccessException](./details_memberaccessexception/) | MemberAccessException is thrown when access to non-existent class' member is attempted or when access to the member is not permitted. Never create instances of this class manually. Use the MemberAccessException class instead. Never wrap the MemberAccessException class instances into [System::SmartPtr](./smartptr/). |
| [Details_MethodAccessException](./details_methodaccessexception/) | MemberAccessException is thrown when access to non-existent method is attempted or when access to the method is not permitted. Never create instances of this class manually. Use the MethodAccessException class instead. Never wrap the MethodAccessException class instances into [System::SmartPtr](./smartptr/). |
| [Details_NotImplementedException](./details_notimplementedexception/) | NotImplementedException is thrown when a method that is not implemented and serves as a stub. Never create instances of this class manually. Use the NotImplementedException class instead. Never wrap the NotImplementedException class instances into [System::SmartPtr](./smartptr/). |
| [Details_NotSupportedException](./details_notsupportedexception/) | NotSupportedException is thrown when a method being invoked is not supported or when an operation attempted on a stream is not supported. Never create instances of this class manually. Use the NotSupportedException class instead. Never wrap the NotSupportedException class instances into [System::SmartPtr](./smartptr/). |
| [Details_NullReferenceException](./details_nullreferenceexception/) | NullReferenceException is thrown when dereferencing of a null-reference is attempted. Never create instances of this class manually. Use the NullReferenceException class instead. Never wrap the NullReferenceException class instances into [System::SmartPtr](./smartptr/). |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | ObjectDisposedException is thrown when a method is invoked on a disposed object. Never create instances of this class manually. Use the ObjectDisposedException class instead. Never wrap the ObjectDisposedException class instances into [System::SmartPtr](./smartptr/). |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | OperationCanceledException is thrown in a thread upon cancellation of an operation that the thread was executing. CancellationToken member is not implemented. Never create instances of this class manually. Use the OperationCanceledException class instead. Never wrap the OperationCanceledException class instances into [System::SmartPtr](./smartptr/). |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | OverflowException is thrown when an operation results in an overflow. Never create instances of this class manually. Use the OverflowException class instead. Never wrap the OverflowException class instances into [System::SmartPtr](./smartptr/). |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | PlatformNotSupportedException is thrown when a feature does not run on a particular platform. Never create instances of this class manually. Use the PlatformNotSupportedException class instead. Never wrap the PlatformNotSupportedException class instances into [System::SmartPtr](./smartptr/). |
| [Details_RankException](./details_rankexception/) | RankException is thrown when an array argument with the number of dimensions different from the expected is passed to a method. Never create instances of this class manually. Use the RankException class instead. Never wrap the RankException class instances into [System::SmartPtr](./smartptr/). |
| [Details_StackOverflowException](./details_stackoverflowexception/) | StackOverflowException is thrown when the thread's execution stack overflows. Never create instances of this class manually. Use the StackOverflowException class instead. Never wrap the StackOverflowException class instances into [System::SmartPtr](./smartptr/). |
| [Details_SystemException](./details_systemexception/) | A base class for classes that represent system (rather than application) exceptions. Never create instances of this class manually. Use the SystemException class instead. Never wrap the SystemException class instances into [System::SmartPtr](./smartptr/). |
| [Details_TimeoutException](./details_timeoutexception/) | TimeoutException indicates if the time that is allotted for a process or operation is expired. Never create instances of this class manually. Use the TimeoutException class instead. Never wrap the TimeoutException class instances into [System::SmartPtr](./smartptr/). |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | TimeZoneNotFoundException is thrown when time zone information is not found. Never create instances of this class manually. Use the TimeZoneNotFoundException class instead. Never wrap the TimeZoneNotFoundException class instances into [System::SmartPtr](./smartptr/). |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | UnauthorizedAccessException is thrown when access is denied by the operating system because of an I/O error or a security error. Never create instances of this class manually. Use the UnauthorizedAccessException class instead. Never wrap the UnauthorizedAccessException class instances into [System::SmartPtr](./smartptr/). |
| [Details_UriFormatException](./details_uriformatexception/) | UriFormatException is thrown when the format of URI is not valid. Never create instances of this class manually. Use the UriFormatException class instead. Never wrap the UriFormatException class instances into [System::SmartPtr](./smartptr/). |
| [DynamicWeakPtr](./dynamicweakptr/) | Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [EnumValues](./enumvalues/) | Provides meta information about enumeration constants of enum type **E**. |
| [EnumValuesBase](./enumvaluesbase/) | A base class for a class that represents meta information of enumeration type. |
| [EventArgs](./eventargs/) | The base class for classes that represent a context that is passed to the event subscribers when an event is triggered. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ExceptionWrapper](./exceptionwrapper/) | Template that represents wrapper of exceptions that are derived from Exception class. |
| [FlagsAttribute](./flagsattribute/) | Indicates that an enumeration can be treated as a bit field; that is, a set of. |
| [Func](./func/) | Function delegate. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [GC](./gc/) | Represents an emulated Garbage Collection which acts more like a stub which effectively does nothing. This is a static type with no instance services. You should never create instances of it by any means. |
| [Guid](./guid/) | Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [IAsyncResult](./iasyncresult/) | Represents the status of asynchronous operation. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ICloneable](./icloneable/) | Defies a method that enables object cloning - creating a copy of an object. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IComparable](./icomparable/) | Defines a method that compares two objects. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IConvertible](./iconvertible/) | Defines methods that convert the value of the implementing reference or value type to a common language runtime type that has an equivalent value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ICustomFormatter](./icustomformatter/) | Defines a method that performs custom formatting of a string representation of a value represented by the specified object. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IDisposable](./idisposable/) | Defines method that releases resources owned by the current object. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IEquatable](./iequatable/) | Defines a method that determines the equality of two objects. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IFormatProvider](./iformatprovider/) | Defines a method that provides formatting information. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IFormattable](./iformattable/) | Defines a method that formats the value of the current object using the specified format string and format provider. |
| [Int16](./int16/) | Contains methods to work with the 16-bit integer. |
| [Int32](./int32/) | Contains methods to work with the 32-bit integer. |
| [Int64](./int64/) | Contains methods to work with the 64-bit integer. |
| [LockContext](./lockcontext/) | Guard object implementing C# lock() statement. |
| [MarshalByRefObject](./marshalbyrefobject/) | Provides access to objects across application domain boundaries in remoting-enabled applications. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Nullable](./nullable/) | Forward declaration. |
| [NullableUtils](./nullableutils/) | Represents C# [System.Nullable](./nullable/) (with no type arguments) static class. Unable to use original name due inability to overload class templates in C++. Supports a value type that can be assigned null. This class cannot be inherited. |
| [Object](./object/) | Base class that enables using methods available for [System.Object](./object/) class in C#. All non-trivial classes used with translated environment should inherit it. |
| [ObjectExt](./objectext/) | Provides static methods that emulate C# [Object](./object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means. |
| [ObjectType](./objecttype/) | Provides static methods that implement object type getters. This is a static type with no instance services. You should never create instances of it by any means. |
| [OperatingSystem](./operatingsystem/) | Represents a particular operating system and provides information about it. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Random](./random/) | Represents a pseudo-random number generator. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ScopedCulture](./scopedculture/) | Represents a culture used within the scope. |
| [SmartPtr](./smartptr/) | Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](./object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](./object/) itself or in counter structure which is tied to [Object](./object/) instance tightly. In any case, all [SmartPtr](./smartptr/) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./smartptr/) is safe given there are other [SmartPtr](./smartptr/) instances holding shared references to the same object. [SmartPtr](./smartptr/) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](./object/) is being deleted when the last 'shared' [SmartPtr](./smartptr/) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./smartptr/) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](./weakptr/) pointer class or [System::SmartPtrMode::Weak](./smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) method or [System::DynamicWeakPtr](./dynamicweakptr/) class. [SmartPtr](./smartptr/) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [SmartPtrInfo](./smartptrinfo/) | Service class to test and alter [SmartPtr](./smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](./smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class. |
| [String](./string/) | [String](./string/) class used across the library. Is a substitute for C# [System.String](./string/) when translating code. For optimization reasons, isn't considered an [Object](./object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [StringComparer](./stringcomparer/) | Compares strings using different comparison modes. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [StringHashCompiletime](./stringhashcompiletime/) | A helper class that generates a hash value from a c-string. |
| [TimeSpan](./timespan/) | Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [TimeZone](./timezone/) | Represents a time zone. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [TimeZoneInfo](./timezoneinfo/) | Represents an information destribing a particular time zone. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Tuple](./tuple/) | Class that represents a tuple data structure. Maximum number of items is 8. |
| [TupleFactory](./tuplefactory/) | Provides static methods for creating tuple objects. |
| [TypeInfo](./typeinfo/) | Represents a particular type and provides information about it. |
| [Uri](./uri/) | Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UriBuilder](./uribuilder/) | Provides methods to construct and modify universial resource identifiers (URIs). Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UriParser](./uriparser/) | Used to parse a new URI scheme. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UriShim](./urishim/) | Service class. |
| [ValueTuple](./valuetuple/) | Class that represents a [ValueTuple](./valuetuple/) data structure. |
| [ValueType](./valuetype/) | Baseclass for value types with [Object](./object/) inheritance being truncated for performance reasons. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Version](./version/) | Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Subclass of [System::SmartPtr](./smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](./smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | Represents a weak reference, which references an object while still allowing that object to be deleted. |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | Represents a weak reference, which references an object while still allowing that object to be deleted. |
## Structures

| Struct | Description |
| --- | --- |
| [CastResult](./castresult/) | Template magic to deduce cast results. |
| [CollectionAssertHelper](./collectionasserthelper/) | Heler API for collection-related operations. |
| [Convert](./convert/) | The structure that contains methods performing conversion of values of one type to the values of another type. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Double](./double/) | Contains methods to work with the double-precision floating-point number. |
| [Enum](./enum/) | Provides methods that perform some operations on values of enum type. This is a static type with no instance services. You should never create instances of it by any means. |
| [EnumGetNameHelper](./enumgetnamehelper/) | Helper class that provides functionality of geting the strting name of enum constant. |
| [EnumParseHelper](./enumparsehelper/) | Helper class that provides functionality of converting a string representation of enum consnant into equivalent enum value. |
| [Environment](./environment/) | [Environment](./environment/) services. This is a static type with no instance services. You should never create instances of it by any means. |
| [HolderInitializer](./holderinitializer/) | This class used to get persistent reference to the object instance, whatever it is lvalue or rvalue. To ubtain such reference, use 'HoldIfTemporary' method, that has there overloads. Two of them take rvalue as a parameter, and just return the reference to it. The third one, in opposite, takes lvalue as a parameter, makes a pointer copy, then return reference to that copy. Also, class has 'Hold' method to hold passed value unconditionally (used to copy values of a local on-stack variables or it's child references) |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | [HolderInitializer](./holderinitializer/) specialization for the case when T is a value type., The usage context allow to return reference to temporary objects, as it is guaranteed, that the instance will be copied by caller. So, this specialization is used just as a stub, and do nothing. |
| [IsBoxable](./isboxable/) | Template predicate that checks if boxing of the specified type is supported. |
| [IsExceptionWrapper](./isexceptionwrapper/) | A template predicate that determines if the specified type is a Exception class or its descendant. |
| [IsNullable](./isnullable/) | A template predicate that determines if its template argument T in [Nullable](./nullable/) or its subclass. |
| [IsSmartPtr](./issmartptr/) | Trait class to check if a type is a specialization of [SmartPtr](./smartptr/) class. |
| [IsStringByteSequence](./isstringbytesequence/) | Template magic to check if a type is a sequence of string characters. |
| [IsStringLiteral](./isstringliteral/) | Template magic to check if a type is a string literal. |
| [IsStringPointer](./isstringpointer/) | Template magic to check if a type is a pointer to character string. |
| [IsWeakPtr](./isweakptr/) | Traits class to check if specific class is a specialization of [System::WeakPtr](./weakptr/). Doesn't check if instance is actually in weak mode. |
| [MakeConstRef](./makeconstref/) | Trait to make generic type \"const reference\" if it is [String](./string/) or a SmartPtr<> type. |
| [Math](./math/) | Contains math functions. This is a static type with no instance services. You should never create instances of it by any means. |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | Defines tuple to store method arguments. |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | Defines tuple to store method arguments. |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | Defines tuple to store method arguments. |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | Represents a pointer to [TypeInfo](./typeinfo/) object that contains information about MulticastDelegate class. |
| [RemoveShared](./removeshared/) | Trait structs to remove SharedPtr/WeakPtr from argument type. |
| [SByte](./sbyte/) | Contains methods to work with the 8-bit integer. |
| [ScopeGuard](./scopeguard/) | The service class that provides services for running a particular function object when an instance of the class goes out of scope. |
| [Single](./single/) | Contains methods to work with the single-precision floating-point number. |
| [TestCompare](./testcompare/) | Service structure providing interface to compare collections. |
| [TestTools](./testtools/) | Provides a set of useful methods that check some basic properties of different types and functions. |
| [TestToolsExt](./testtoolsext/) | Common functions to be used by testing translation. |
| [TypeInfoPtr](./typeinfoptr/) | Wrapper for a pointer to an instance of [TypeInfo](./typeinfo/) class. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [UInt16](./uint16/) | Contains methods to work with the unsigned 16-bit integer. |
| [UInt32](./uint32/) | Contains methods to work with the unsigned 32-bit integer. |
| [UInt64](./uint64/) | Contains methods to work with the unsigned 64-bit integer. |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | Represents a pointer to [TypeInfo](./typeinfo/) object that contains information about [ValueTuple](./valuetuple/) class. |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | Trait struct to convert argument type to a weak-pointer, if it is a pointer type. |
## Functions

| Function | Description |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | A factory function that constructs a new [Array](./array/) object, fills it with the elements from the specified initialization list and returns a smart pointer pointing to the [Array](./array/) object. |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | A factory function that constructs a new [Array](./array/) object passing the specified arguments to its constructor. |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | A factory function that constructs a new [Array](./array/) object passing the specified arguments to its constructor. |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Determines if the specified [Nullable](./nullable/) object represents a value that is equal to null. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Determines if the specified value is equal to the value represented by the specified [Nullable](./nullable/) object by applying [operator==()](./operator_equal_equal/) to these values. |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | Equal-compares two smart pointers. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | Checks if smart pointer is null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | Equality comparison smart pointer against simple (C) pointer. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | Equality comparison smart pointer against simple (C) pointer. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | Checks if value type object (translated C# structure, etc.) is null. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | Checks if value type object (translated C# structure, etc.) is null. |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) comparison. |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) comparison. |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) and string comparison. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | Checks if string is null. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | Determines if the URIs represented by the current and specified objects are equal. |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Determines if the specified [Nullable](./nullable/) object represents a value that is not equal to null. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Determines if the specified value is not equal to the value represented by the specified [Nullable](./nullable/) object by applying [operator!=()](./operator_not_equal/) to these values. |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | Non-equal-compares two smart pointers. |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | Checks if smart pointer is not null. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | Checks if smart pointer is not null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | Inequality comparison smart pointer against simple (C) pointer. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | Equality comparison smart pointer against simple (C) pointer. |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) comparison. |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) comparison. |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) and string comparison. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | Checks if string is null. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | Determines if the URIs represented by the current and specified objects are not equal. |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Always returns false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Determines if the specified value is less than the value represented by the specified [Nullable](./nullable/) object by applying [operator<()](./operator_less/) to these values. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Always returns false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Determines if the specified value is less or equal to the value represented by the specified [Nullable](./nullable/) object by applying [operator<=()](./operator_less_equal/) to these values. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Always returns false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Determines if the specified value is greater than the value represented by the specified [Nullable](./nullable/) object by applying [operator>()](./operator_greater/) to these values. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Always returns false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Determines if the specified value is greater or equal to the value represented by the specified [Nullable](./nullable/) object by applying [operator>=()](./operator_greater_equal/) to these values. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | Writes the value represented by the specified object to the specified output stream. |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | Prints string to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | Prints value to ostream. Mostly used for debug. |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | Prints value to ostream. Mostly used for debug. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | Outputs a string to the output stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | Outputs a string to the output stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | Insert data into the stream. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | Insert data into the stream. |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | Calculates the number of days between two days of week. |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | Returns a new instance of [Decimal](./decimal/) class that represents a value that is the result of subtraction of the value represented by the specified [Decimal](./decimal/) object from the specified value. |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | Disconnects all callbacks in right hand delegate from the end of left hand delegate callback list. |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Subtracts non-nullable and nullable values. |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | Returns a new instance of [Decimal](./decimal/) class that represents a value that is a sum of the specified value and the value represented by the specified [Decimal](./decimal/) object. |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | Connects all callbacks from right hand delegate to the end of left hand delegate callback list. |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Sums non-nullable and nullable values. |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) concatenation. |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) concatenation. |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) concatenation. |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | Returns a new instance of [Decimal](./decimal/) class that represents a value that is a result of multiplication of the specified value and the value represented by the specified [Decimal](./decimal/) object. |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | Returns a new instance of [Decimal](./decimal/) class that represents a value that is a result of division of the specified value and the value represented by the specified [Decimal](./decimal/) object. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | Returns the reference to the single default-constructed instance of the exception type. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | Returns the reference to the single default-constructed instance of the non-exception type. |
| T\& [Discard](./discard/)(T\&&) | Returns the default-constructed temporary instance of the specified type, which can be placed instead of discarding '_' argument. |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | The sigle function that emulates behavior of C#'s try[-catch]-finally statement. During translation of C#'s try[-catch]-finally statement with translator's option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method. |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | The sigle function that emulates behavior of C#'s try[-catch]-finally statement. During translation of C#'s try[-catch]-finally statement with translator's option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method. This overload handles the case in which the return value of the function object that implements the try[-catch] part of the try[-catch]-finally statement is bool. |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | The sigle function that emulates behavior of C#'s try[-catch]-finally statement. During translation of C#'s try[-catch]-finally statement with translator's option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method. This overload handles the case in which the return value of the function object that implements the try[-catch] part of the try[-catch]-finally statement is bool&. |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | Creates reference to [DynamicWeakPtr](./dynamicweakptr/) object. Used by translator when passing function arguments by reference. |
| T\& [Ref](./ref/)(T\&) | Helper function to acquire references to objects. Used to guarantee that [System::DynamicWeakPtr](./dynamicweakptr/) updates referenced object after assignments. |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with target type argument for (auto& value : IterateOver<SomeType>(enumerable)) |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with default target type argument for (auto& value : IterateOver(enumerable)) analog to the following C# code foreach (var value in enumerable) |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with default target type argument for (auto& value : IterateOver(enumerable)) |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with target type same as original value_type of iterator. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with different target type and original value_type of iterator. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable this with default target type. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with target type argument for (auto& value : IterateOver<SomeType>(enumerable)) |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Returns a hash code for the specified scalar value. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Returns a hash code for the specified object. |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Returns a hash code for the specified object which is exception. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Returns a hash code for the specified object which is not a smart pointer nor exception. |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | Specialization for std::thread::id; Returns the hash code for the specified thread object. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs cast on [SmartPtr](./smartptr/) objects. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs cast on [SmartPtr](./smartptr/) objects. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | Old obsolete casts. Will be removed in future versions. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs dynamic cast on [SmartPtr](./smartptr/) objects. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Performs dynamic cast on Objects to Exception objects. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | Performs dynamic cast on Exception objects. |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs dynamic cast on [SmartPtr](./smartptr/) objects. |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | Unboxes boxed enum via cast. |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | Performs dynamic cast of null objects. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | Performs dynamic cast on non-pointer objects. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | Performs dynamic cast on Objects to Exception objects. |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | Performs dynamic cast from IntPtr to pointer. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs static cast on [SmartPtr](./smartptr/) objects. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | Performs static cast on [WeakPtr](./weakptr/) objects. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | Performs static cast on Exception objects. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Performs static cast on Objects to Exception objects. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs static cast on [SmartPtr](./smartptr/) objects. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | Performs static cast on [WeakPtr](./weakptr/) objects. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | Performs static cast of null objects. |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | Specialization for arithmetic types. |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | Process cast from [String](./string/) to [String](./string/). |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | Specialization for arithmetic types. |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | Performs static cast on non-pointer objects. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | Performs static cast on Exception objects. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | Performs static cast on Objects to Exception objects. |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | End of deprecated casts. |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Performs real static cast on [SmartPtr](./smartptr/) objects. |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | Performs memberwise cloning using copy constructor. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used when the source and the result types are the same. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used when simple constructor-like cast is needed. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for exception wrappers. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for casting object to exception. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used when the source and result both are smart pointers (without expicit SmartPtr<...> in result type). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | Casts the source type to the result type using explicit cast. Used when the casting raw pointer to smart pointer. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used when the source and result both are smart pointers (with expicit SmartPtr<...> in result type). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for unboxing object to nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used to box nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for unboxing nullable object. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for enum boxing. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for common boxing. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for [System::String](./string/) boxing. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for common unboxing. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for nullptr casting. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Casts the source type to the result type using explicit cast. Used for casting between arrays. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used when simple constructor-like cast is needed. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used when the source and the result types are the same. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for exception wrappers. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for casting object to exception. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used when the source and result both are smart pointers. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used when the source and result both are smart pointers (with expicit SmartPtr<...> in result type). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for unboxing object to nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | Invalid unboxing to non-object type. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for boxing nullable object. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for boxing common object. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for string unboxing. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used for nullptr casing. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Casts the source type to the result type using 'as' operator cast. Used to cast between arrays. |
| static auto [SafeInvoke](./safeinvoke/)(T0, T1) | Implementation of '?.' operator translation. |
| **bool** [IsDeclaration](./isdeclaration/)(const ExpressionT\&, ResultT\&) | Implements 'is' declaration pattern translation. |
| **bool** [IsConstant](./isconstant/)(const ExpressionT\&, const ConstantT\&) | Implements 'is' constant pattern translation. |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | Implements typeof() translation. Overload for [String](./string/). |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | Implements typeof() translation. Overload for [DateTime](./datetime/). |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | Determines the equality of two values applying [operator==()](./operator_equal_equal/) to them. |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | Specialization for single-precision floating point values. Although two floating point NaNs are defined by IEC 60559:1989 to always compare as unequal, the contract for [System.Object.Equals](./object/equals/), requires that overrides must satisfy the requirements for an equivalence operator. Therefore, System.Double.Equals and System.Single.Equals return True when comparing two NaNs, while the equality operator returns False in that case, as required by the standard. |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | Specialization for double-precision floating point values. |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | Compares two values. |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | Compares two floating point values. |
| **bool** [IsNaN](./isnan/)(const T\&) | Determines if the specified value is Not-A-Number value. |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | Determines if the specified value represents infinity. |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | Determines if the specified value represents positive infinity. |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | Determines if the specified value represents negative infinity. |
| TTo [CheckedCast](./checkedcast/)(TFrom) | Determines if the specified value falls into the range of values of type **TTo** and if it does casts it to the type **TTo**. |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | A factory function that creates instances of ScopedGuard class. |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | Overload for static setter functions with type conversion. |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | Overload for instance setter functions with type conversion. |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function. |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | Translator translates C#'s post-increment expressions targeting class' property that has setter and getter defined, into invocation of this function. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Translator translates C#'s post-increment expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for non-const getter). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | Translator translates C#'s post-increment expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for const getter). |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | Translator translates C#'s pre-decrement expressions targeting class' property that has setter and getter defined, into invocation of this function. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Translator translates C#'s pre-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for non-const getter). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | Translator translates C#'s pre-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for const getter). |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | Translator translates C#'s post-decrement expressions targeting class' property that has setter and getter defined, into invocation of this function. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Translator translates C#'s post-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for non-const getter). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | Translator translates C#'s post-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for const getter). |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | Creates object on heap and returns shared pointer to it. |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | Creates object on heap and returns shared pointer to it. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | Converts raw pointer to smart pointer. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | Converts raw pointer to smart pointer. Overload for const pointers. Useful e. g. when using 'this' variable in C# methods translated as const. |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | Casts smart pointers using static_cast. |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | Casts smart pointers using dynamic_cast. |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | Casts smart pointers using const_cast. |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | Gets referenced object of smart pointer. |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | Performs the explicit casting of elements of the specified enumerable object to different type. |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | Performs the explicit casting of elements of the specified enumerable object to different type. |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | Performs casting of elements of the specified array to different type. Override for cases then From is [SmartPtr](./smartptr/) obj. |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | Performs casting of elements of the specified array to different type. Override for cases then From is Boxable and To is [Object](./object/)[]. |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | Performs casting of elements of the specified array to different type. |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | Gets a string from the input streamusing UTF-8 encoding. |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | Gets a string from the input stream. |
| static [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | Creates tuple on stack. |
| static [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | Creates tuple bound to some values. |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |
## Enums

| Enum | Description |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Enumeration containing values that represent different formats of base-64 encoded data. |
| [DateTimeKind](./datetimekind/) | Enumeration values of which represent the kinds of date and time. |
| [DayOfWeek](./dayofweek/) | Enumeration that represents a day of week. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Specifies the environment variable location. |
| [MidpointRounding](./midpointrounding/) | Specifies the behavior of rounding functions. |
| [PlatformID](./platformid/) | Represents an operating system platform. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) pointer type: weak or shared. Defines whether pointer is being counted when it is being decided whether to delete object or not. |
| [StringSplitOptions](./stringsplitoptions/) | Determines string splitting behavior. |
| [StringComparison](./stringcomparison/) | Defines string comparison style. |
| [TypeCode](./typecode/) | Represents the type of an object. |
| [UriKind](./urikind/) | Represents the kinds of URIs. |
| [UriComponents](./uricomponents/) | Represents URI components. |
| [UriFormat](./uriformat/) | Specifies how the URI is escaped. |
| [UriHostNameType](./urihostnametype/) | Represents the type of host name. |
| [UriPartial](./uripartial/) | Represents the parts of a URI for the [Uri.GetLeftPart](./uri/getleftpart/) method. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | An alias for a smart pointer that points to an instance of [System::IFormatProvider](./iformatprovider/) class. |
| [DecoderFallbackPtr](./decoderfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::DecoderFallback](../system.text/decoderfallback/) class. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | An alias for a smart pointer that points to an instance of [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) class. |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) class. |
| [EncoderFallbackPtr](./encoderfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderFallback](../system.text/encoderfallback/) class. |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) class. |
| [EncoderPtr](./encoderptr/) | An alias for a smart pointer that points to an instance of [System::Text::Encoder](../system.text/encoder/) class. |
| [DecoderPtr](./decoderptr/) | An alias for a smart pointer that points to an instance of [System::Text::Decoder](../system.text/decoder/) class. |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) class. |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) class. |
| [EncodingPtr](./encodingptr/) | An alias for a smart pointer that points to an instance of [System::Text::Encoding](../system.text/encoding/) class. |
| [EncodingInfoPtr](./encodinginfoptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncodingInfo](../system.text/encodinginfo/) class. |
| [StreamPtr](./streamptr/) | An alias for a smart pointer that points to an instance of [System::IO::Stream](../system.io/stream/) class. |
| [FileStreamPtr](./filestreamptr/) | An alias for a smart pointer that points to an instance of [System::IO::FileStream](../system.io/filestream/) class. |
| [MemoryStreamPtr](./memorystreamptr/) | An alias for a smart pointer that points to an instance of [System::IO::MemoryStream](../system.io/memorystream/) class. |
| [StreamReaderPtr](./streamreaderptr/) | An alias for a smart pointer that points to an instance of [System::IO::StreamReader](../system.io/streamreader/) class. |
| [StreamWriterPtr](./streamwriterptr/) | An alias for a smart pointer that points to an instance of [System::IO::StreamWriter](../system.io/streamwriter/) class. |
| [FileInfoPtr](./fileinfoptr/) | An alias for a smart pointer that points to an instance of [System::IO::FileInfo](../system.io/fileinfo/) class. |
| [FileSystemInfoPtr](./filesysteminfoptr/) | An alias for a smart pointer that points to an instance of [System::IO::FileSystemInfo](../system.io/filesysteminfo/) class. |
| [DirectoryInfoPtr](./directoryinfoptr/) | An alias for a smart pointer that points to an instance of [System::IO::DirectoryInfo](../system.io/directoryinfo/) class. |
| [Action](./action/) | Delegate type that references methods that have no return value. |
| [ByteArrayPtr](./bytearrayptr/) | An alias for a smart pointer object that points to an array of unsigned 8-bit integers. |
| [AsyncCallback](./asynccallback/) | A delegate type that represents a method to be called when asynchronous operation completes. |
| [BadImageFormatException](./badimageformatexception/) | The exception that is thrown when the file image of a dynamic link library (DLL) or an executable program is invalid. Never wrap the BadImageFormatException class instances into [System::SmartPtr](./smartptr/). |
| [Converter](./converter/) | Represents a pointer to the invokable entity that accepts a single argument of the **TInput** type and returns a value of the **TOutput** type. |
| [Event](./event/) | Represents an event - a mechanism through which subscribers are notified about an occurence of interest by means of a delegate invocation. |
| [EventArgsPtr](./eventargsptr/) | Shared pointer to an instance of [EventArgs](./eventargs/) class. |
| [EventHandler](./eventhandler/) | Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [ExceptionPtr](./exceptionptr/) | Type alias used by exception wrappers. |
| [Exception](./exception/) | Alias to be used instead of Details::Exception. |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | Shared pointer to [IAsyncResult](./iasyncresult/). |
| [MakeConstRef_t](./makeconstref_t/) | Helper type for [MakeConstRef](./makeconstref/) modifier. |
| [Predicate](./predicate/) | Represents a pointer to a predicate - an invokable entity that accepts a single argument and returns a bool value. |
| [ArrayPtr](./arrayptr/) | Alias for 'pointer to array' type. |
| [SharedPtr](./sharedptr/) | Alias for smart pointer widely used in the library. |
| [StringComparerPtr](./stringcomparerptr/) | An alias for a shared pointer to an instance of [StringComparer](./stringcomparer/) class. |
| [TimeZonePtr](./timezoneptr/) | Shared pointer to an instance of [TimeZone](./timezone/) class. |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Alias for shared pointer to an instance of [TimeZoneInfo](./timezoneinfo/) class. |
