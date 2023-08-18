---
title: Semaphore()
second_title: Aspose.Slides for C++ API Reference
description: Creates unnamed semaphore.
type: docs
weight: 1
url: /system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) constructor


Creates unnamed semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initialCount | int | Initial count of active entries. |
| maximumCount | int | Maximum allwed entries count. |

## Semaphore::Semaphore(int, int, const String\&) constructor


Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initialCount | int | Initial count of active entries. |
| maximumCount | int | Maximum allwed entries count. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) name. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) constructor


Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initialCount | int | Initial count of active entries. |
| maximumCount | int | Maximum allwed entries count. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) name. |
| createdNew | **bool**\& | Reference to variable which is set to true if semaphore was created and to false if existing one with same name was reused |

## See Also

* Class [Semaphore](../)
* Class [String](../../../system/string/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)