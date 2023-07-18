---
title: PrintToStringImpl()
second_title: Aspose.Slides for C++ API Reference
description: "Prints System::Object subclass to string using ToString() method."
type: docs
weight: 14
url: /cpp/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) function


Prints [System::Object](../../system/object/) subclass to string using ToString() method.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Final class type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pointer to object to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

[String](../../system/string/) representation of object passed or \"nullptr\", if **value** is null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) function


Prints [System::Object](../../system/object/) subclass to string using ToString() method.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Final class type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Pointer to object to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

[String](../../system/string/) representation of object passed or \"nullptr\", if **value** is null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function


Prints object to string using ToString() method.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

[String](../../system/string/) representation of object passed.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function


Prints object to string using PrintTo method.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

[String](../../system/string/) representation of object passed.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function


Prints object to string using PrintTo method.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

[String](../../system/string/) representation of object passed.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) function


Prints pair to string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | First pair type argument. |
| T2 | Second pair type argument. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

Joint string representations of both first and second pair components.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) function


Prints pair to string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | First pair type argument. |
| T2 | Second pair type argument. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

Joint string representations of both first and second pair components.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function


Prints STL-style containers to string by printing their elements (not more than 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

Joint string representations of contained elements.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) function


Prints other types to string by using gtest-provided functions.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | int | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Return Value

[String](../../system/string/) representations of object passed.

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [WeakPtr](../../system/weakptr/)
* Class [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Class [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)