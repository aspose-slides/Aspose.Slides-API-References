---
title: CompareTo()
second_title: Aspose.Slides for C++ API Reference
description: Compares current and the specified objects.
type: docs
weight: 27
url: /system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const method


Compares current and the specified objects.

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../) | The [TimeSpan](../) object to compare the current object with |

### Return Value

-1 if the current object represents the interval that is shorter than **value**; 0 if the current object represents the interval that is equal to **value**; 1 if the current object represents the interval that is longer than **value**

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const method


Compares current and the specified objects.

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The [TimeSpan](../) object to compare the current object with |

### Return Value

-1 if the current object represents the interval that is shorter than **value**; 0 if the current object represents the interval that is equal to **value**; 1 if the current object represents the interval that is longer than **value**

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)