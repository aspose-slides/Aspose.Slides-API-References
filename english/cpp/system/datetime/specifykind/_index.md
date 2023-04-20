---
title: SpecifyKind()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new DateTime object that represents the same number of ticks as the specified DateTime object and represents local time, UTC time or neither as specified by the argument kind.
type: docs
weight: 833
url: /cpp/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) method


Constructs a new [DateTime](../) object that represents the same number of ticks as the specified [DateTime](../) object and represents local time, UTC time or neither as specified by the argument **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | The [DateTime](../) object to copy the number of ticks from |
| kind | [DateTimeKind](../../datetimekind/) | Specifies if the new object should represent local time, UTC time or neither. |

### Return Value

A new [DateTime](../) object that represents the same number of ticks as **value** and DateTimeKind value specified by **kind**.

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)