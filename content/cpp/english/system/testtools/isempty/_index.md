---
title: IsEmpty()
second_title: Aspose.Slides for C++ API Reference
description: Checks if string is empty.
type: docs
weight: 14
url: /system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) method


Checks if string is empty.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) to check for being empty. |

### Return Value

True if string is empty (null-length), false otherwise.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) method


Checks if collection is empty.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
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

True if collection has zero element count, false otherwise.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)