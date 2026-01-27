---
title: GetHashCode()
second_title: Aspose.Slides for C++ API Reference
description: Returns a hash code for the specified scalar value.
type: docs
weight: 2419
url: /system/gethashcode/
---
## System::GetHashCode(const T\&) function


Returns a hash code for the specified scalar value.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the value for which the function generates hash code |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The value to generate hash code for |

### Return Value

The hash code generated for the specified value

## System::GetHashCode(const T\&) function


Returns a hash code for the specified object.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The [SmartPtr](../smartptr/) pointing to the object to generate hash code for |

### Return Value

The hash code generated for the specified object

## System::GetHashCode(const T\&) function


Returns a hash code for the specified object which is exception.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The Exception Wrapper that contains the object to generate hash code for |

### Return Value

The hash code generated for the specified object

## System::GetHashCode(const T\&) function


Returns a hash code for the specified object which is not a smart pointer nor exception.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | A const reference to the object to generate hash code for |

### Return Value

The hash code generated for the specified object

## System::GetHashCode(const std::thread::id\&) function


Specialization for std::thread::id; Returns the hash code for the specified thread object.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## See Also

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)