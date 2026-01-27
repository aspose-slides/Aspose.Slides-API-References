---
title: Handle()
second_title: Aspose.Slides for C++ API Reference
description: Invokes a handler function on each inner exception and rethrows any unhandled exceptions.
type: docs
weight: 66
url: /system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method


Invokes a handler function on each inner exception and rethrows any unhandled exceptions.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | A function that takes an Exception and returns true if it is handled. |
## Remarks



If all exceptions are handled, the method returns normally; otherwise, a new AggregateException containing the unhandled exceptions is thrown. 

## See Also

* Typedef [Exception](../../exception/)
* Class [Func](../../func/)
* Class [Details_AggregateException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)