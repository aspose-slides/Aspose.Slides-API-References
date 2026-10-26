---
title: Cancel()
second_title: Aspose.Slides C++ API hivatkozás
description: Közli a leállítási kérést.
type: docs
weight: 40
url: /hu/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() módszer


Közli a leállítási kérést.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Megjegyzések


Az összes regisztrált visszahívás végrehajtásra kerül. 
A későbbi hívások a [get_IsCancellationRequested()](../get_iscancellationrequested/) esetén true értéket adnak vissza. 
A visszahívások szinkron módon hajtódnak végre ebben a hívásban. 

## Lásd még

* Osztály [CancellationTokenSource](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)