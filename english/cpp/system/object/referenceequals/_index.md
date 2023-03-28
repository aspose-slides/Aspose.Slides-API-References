---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ API Reference
description: "Specialization of Object::ReferenceEquals for case of string and nullptr."
type: docs
weight: 261
url: /cpp/system/object/referenceequals/
---
## Object::ReferenceEquals([String](../../string/) const\&, std::nullptr_t) method


Specialization of [Object::ReferenceEquals](./) for case of string and nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) to compare to nullptr. |

### Return Value

true if string is null, false otherwise.

## See Also

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::ReferenceEquals([String](../../string/) const\&, [String](../../string/) const\&) method


Specialization of [Object::ReferenceEquals](./) for case of strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | First string to compare. |
| str2 | [String](../../string/) const\& | Second string to compare. |

### Return Value

true if strings match, false otherwise.

## See Also

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::ReferenceEquals([ptr](../ptr/) const\&, [ptr](../ptr/) const\&) method


Compares objects by reference.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | First pointer to compare. |
| objB | [ptr](../ptr/) const\& | Second pointer to compare. |

### Return Value

True if pointers match and false otherwise.

## See Also

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::ReferenceEquals(T const\&, T const\&) method


Compares objects by reference.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of objects to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T const\& | First object to compare. |
| objB | T const\& | Second object to compare. |

### Return Value

True if object addresses match and false otherwise.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Reference-compares value type object with nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of object to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T const\& | First object to compare. |

### Return Value

Always returns false as value types cannot be nulled.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
