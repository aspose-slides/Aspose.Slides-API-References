---
title: SmartPtr()
second_title: Aspose.Slides for C++ API Reference
description: Creates SmartPtr object of required mode.
type: docs
weight: 1
url: /system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Creates [SmartPtr](../) object of required mode.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Creates null-pointer [SmartPtr](../) object of required mode.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Creates [SmartPtr](../) pointing to specified object, or converts raw pointer to [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Copy constructs [SmartPtr](../) object. Both pointers point to the same object afterwards.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Copy constructs [SmartPtr](../) object. Both pointers point to the same object afterwards. Performs type conversion if allowed.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type of object pointed by x. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Move constructs [SmartPtr](../) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Type of source array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointer to array to create a copy of, but with different type of elements. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const Y\&) constructor


Initializes empty array. Used to translate some C# code constructs.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Constructs a [SmartPtr](../) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Another smart pointer to share the ownership to the ownership from. |
| p | [Pointee_](../pointee_/) * | Pointer to an object to manage. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// This class contains a field that will be printed.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// This class contains an instance of the Foo class.
class Bar : public System::Object
{
public:
  Foo data;
};

// Used to print a string from the Foo-class instance.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Prints the number of shared pointers pointing to the object.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Create SharedPtr to an instance of the Bar class.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Create SharedPtr that will point to the field of the Bar-class instance.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Make the 'bar' pointer pointing to nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data still exists and the 'foo' pointer is valid.
  PrintMessage(foo);

  return 0;
}
/*
This code example produces the following output:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)