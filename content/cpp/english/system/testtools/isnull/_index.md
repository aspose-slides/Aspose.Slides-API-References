---
title: IsNull()
second_title: Aspose.Slides for C++ API Reference
description: Checks if specific value is null. Version for arithmetic and enum types.
type: docs
weight: 1
url: /system/testtools/isnull/
---
## TestTools::IsNull(T) method


Checks if specific value is null. [Version](../../version/) for arithmetic and enum types.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | Value to check for null. |

### Return Value

Always returns false.

## TestTools::IsNull(const T\&) method


Checks if specific value is null. [Version](../../version/) for non-arithmetic and non-enum value types.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Value to check for null. |

### Return Value

True if object is compared to nullptr as true, false otherwise.

## TestTools::IsNull(const SharedPtr\<T\>\&) method


Checks if specific value is null. [Version](../../version/) for non-arithmetic value types.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Value to check for null. |

### Return Value

True if object is compared to nullptr as true, false otherwise.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) method


Checks if specific value is null. [Version](../../version/) for key-value pairs.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Pair object. |

### Return Value

True if pair is considered null, false otherwise.

## TestTools::IsNull(const System::String\&) method


Checks if string is null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) to check. |

### Return Value

True if string is considered null, false otherwise.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)