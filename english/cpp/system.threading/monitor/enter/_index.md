---
title: Enter()
second_title: Aspose.Slides for C++ API Reference
description: Acquires an exclusive lock on a specified object.
type: docs
weight: 1
url: /cpp/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) method


Acquires an exclusive lock on a specified object.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | The object on which to acquire the monitor lock. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) method


Acquires an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)