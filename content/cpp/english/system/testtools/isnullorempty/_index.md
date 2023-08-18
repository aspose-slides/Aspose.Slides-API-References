---
title: IsNullOrEmpty()
second_title: Aspose.Slides for C++ API Reference
description: Checks if collection is null or empty.
type: docs
weight: 27
url: /system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) method


Checks if collection is null or empty.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Collection type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collection to check. |

### Return Value

True if collection is null or has zero element count, false otherwise.

## TestTools::IsNullOrEmpty(const System::String\&) method


Checks if string is null or empty.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) to check. |

### Return Value

True if string is null or has zero length, false otherwise.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)