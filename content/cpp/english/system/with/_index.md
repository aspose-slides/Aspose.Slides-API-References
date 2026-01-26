---
title: With()
second_title: Aspose.Slides for C++ API Reference
description: Clones reference record and applies initializer functor to it.
type: docs
weight: 2549
url: /system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) function


Clones reference record and applies initializer functor to it.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Record type to clone. |
| A | Initialization functor type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Shared pointer to the object to clone and initialize. |
| initializer | const A\& | Initialization functor being applied to record clone. |

### Return Value

Shared pointer to cloned record.

## System::With(const T\&, const A\&) function


Copies struct record and applies initializer functor to it.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Record type to copy. |
| A | Initialization functor type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| record | const T\& | Record to copy and initialize. |
| initializer | const A\& | Initialization functor being applied to record copy. |

### Return Value

Copied record.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)