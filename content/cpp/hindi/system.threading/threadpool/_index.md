---
title: ThreadPool
second_title: Aspose.Slides for C++ API संदर्भ
description: थ्रेड पूल API जो नौकरियों को कतार में डालने की अनुमति देता है जिसे कार्यकर्ता थ्रेड्स के पूल द्वारा पढ़ा जाता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टांस सेवाएँ नहीं हैं। आपको इसे किसी भी माध्यम से इंस्टांस नहीं बनाना चाहिए।
type: docs
weight: 222
url: /hi/system.threading/threadpool/
---
## ThreadPool क्लास

[Thread](../thread/) pool API जो नौकरियों को कतार में डालने की अनुमति देता है जिसे कार्यकर्ता थ्रेड्स के पूल द्वारा पढ़ा जाता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टांस सेवा नहीं है। आपको इसे किसी भी तरह से इंस्टांस नहीं बनाना चाहिए।

```cpp
class ThreadPool : public System::Object
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| static void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Gets number of available threads. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [ThreadPoolImpl](../threadpoolimpl/)\& [GetInstance](./getinstance/)() | Implementation instance that holds list of jobs and other parameters. |
| static void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Gets maximal number of concurrent threads. |
| static void [GetMinThreads](./getminthreads/)(int\&, int\&) | Gets minimal number of threads being created by pool. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static void [JoinAllThreads](./joinallthreads/)() | Joins all owned threads. Waits infinitely. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| void [operator=](./operator_equal/)(const [ThreadPool](./)\&) | No copying. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/)) | Puts work item into queue which is present with callback with no parameter. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Puts work item into queue which is present with callback with no parameter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| static **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Sets number of threads owned by pool. |
| static **bool** [SetMinThreads](./setminthreads/)(int, int) | Sets minimal number of threads owned by pool. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [ThreadPool](./threadpool/)(const [ThreadPool](./)\&) | No copying. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## टिप्पणी

```cpp
#include "system/threading/thread_pool.h"
#include "system/threading/thread.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>
#include <mutex>
#include <string>
#include <thread>

const std::string &BooleanToString(bool value)
{
  static const std::string True = "True";
  static const std::string False = "False";

  return value ? True : False;
}

int main()
{
  using namespace System::Threading;
  std::mutex m;

  const auto threadsCount = std::thread::hardware_concurrency();

  for (unsigned int i = 0; i < threadsCount; ++i)
  {
    ThreadPool::QueueUserWorkItem([&m](System::SharedPtr<System::Object> object) -> void {
      auto thread = Thread::get_CurrentThread();
      m.lock();
      std::cout << "Background: " << BooleanToString(thread->get_IsBackground()) <<
        ", Thread pool: " << BooleanToString(thread->get_IsThreadPoolThread()) <<
        ", Thread ID: " << thread->get_ManagedThreadId() << std::endl;
      m.unlock();
    });
  }

  ThreadPool::JoinAllThreads();

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 1
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 3
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 5
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 6
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 9
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 1
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 7
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 2
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 4
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 3
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 12
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 8
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 5
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 6
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 16
पृष्ठभूमि: True, थ्रेड पूल: True, थ्रेड ID: 11
*/
```

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Threading](../)
* लाइब्रेरी [Aspose.Slides](../../)