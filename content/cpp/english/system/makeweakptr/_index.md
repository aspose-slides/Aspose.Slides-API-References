---
title: MakeWeakPtr()
second_title: Aspose.Slides for C++ API Reference
description: Converts raw pointer to weak pointer.
type: docs
weight: 2939
url: /system/makeweakptr/
---
## System::MakeWeakPtr(X *) function


Converts raw pointer to weak pointer.

```cpp
template<class X> SmartPtr<X> System::MakeWeakPtr(X *p)
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

Weak smart pointer to object.

## System::MakeWeakPtr(const X *) function


Converts raw pointer to weak pointer. Overload for const pointers. Useful e. g. when using 'this' variable in C# methods translated as const.

```cpp
template<class X> SmartPtr<X> System::MakeWeakPtr(const X *p)
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

Weak smart pointer to object.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)