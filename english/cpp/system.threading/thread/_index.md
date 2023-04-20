---
title: Thread
second_title: Aspose.Slides for C++ API Reference
description: "Thread implementation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 157
url: /cpp/system.threading/thread/
---
## Thread class


[Thread](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Thread : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| void [Abort](./abort/)() | Aborts thread. Not implemented. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | Gets thread culture. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | Gets object which describes current thread. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | Gets user interface culture used by thread. |
| **bool** [get_IsAlive](./get_isalive/)() | Checks whether thread is alive. |
| **bool** [get_IsBackground](./get_isbackground/)() | Checks whether thread is background. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Checks if thread is owned by a thread pool. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | Gets identifier of thread. Can be got from OS, but if OS thread identifier exceeds int limits, ids of threads can intersect. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | Gets thread name. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | Gets thread state. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | Gets identifier of current thread. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| void [Interrupt](./interrupt/)() | Interrupt thread. Not implemented. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Join](./join/)() | Joins managed thread. Performs unlimited waiting if required. |
| **bool** [Join](./join/)(int) | Joins managed thread. Performs limited waiting. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | Joins managed thread. Performs limited waiting. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| static void [MemoryBarrier](./memorybarrier/)() | Synchronizes memory access. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | Copies TLS data from different thread. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Sets thread culture. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Sets user interface culture used by thread. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | Sets thread to background or foreground. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | Sets thread name. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| static void [Sleep](./sleep/)(int) | Stops current thread for specified timeout. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | Stops current thread for specified timeout. |
| static void [SpinWait](./spinwait/)(int) | Waits for specific number of loop iterations. |
| void [Start](./start/)() | Starts thread using null argument object. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Starts thread. |
|  [Thread](./thread/)() | Constructor. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | Constructor. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | Constructor. |
|  [Thread](./thread/)([Thread](./)\&) | Copy constructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| static **bool** [Yield](./yield/)() | Yields thread. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
| virtual  [~Thread](./~thread/)() | Destructor. |
## Remarks



```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
This code example produces the following output:
Main thread ID: 2
Child thread ID: 1
*/
```

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)