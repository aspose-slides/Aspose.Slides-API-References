---
title: Join()
second_title: Aspose.Slides for C++ API Reference
description: Joins array using string as separator.
type: docs
weight: 807
url: /system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) to put between array elements when joining them. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) of parts to join. |
| startIndex | int | First index in array to start joining from. |
| count | int | Number of array elements to join. -1 means 'until array ends'. |

### Return Value

[String](../) representing joint array elements.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) to put between array elements when joining them. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView of parts to join. |
| startIndex | int | First index in array to start joining from. |
| count | int | Number of array elements to join. -1 means 'until array ends'. |

### Return Value

[String](../) representing joint array elements.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) to put between array elements when joining them. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - parts enumerable object |

### Return Value

[String](../) representing joint elements.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) to put between array elements when joining them. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) of parts to join. |

### Return Value

[String](../) representing joint elements.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)