---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API Reference
description: Converts raw pointer to smart pointer.
type: docs
weight: 2822
url: /system/makesharedptr/
---
## System::MakeSharedPtr(X *) function


Converts raw pointer to smart pointer.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | Pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | X * | Raw pointer to object. |

### Return Value

Shared smart pointer to object.

## System::MakeSharedPtr(const X *) function


Converts raw pointer to smart pointer. Overload for const pointers. Useful e. g. when using 'this' variable in C# methods translated as const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | Pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | const X * | Raw pointer to object. |

### Return Value

Shared smart pointer to object.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)