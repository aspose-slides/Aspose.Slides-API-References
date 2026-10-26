---
title: Cancel()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Komunikuje požadavek na zrušení.
type: docs
weight: 40
url: /cs/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() metoda

Komunikuje požadavek na zrušení.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Poznámky

Všechny registrované zpětné volání budou vyvolány.

Následující volání [get_IsCancellationRequested()](../get_iscancellationrequested/) vrátí true.

Zpětná volání jsou prováděna synchronně během tohoto volání.

## Viz také

* třída [CancellationTokenSource](../)
* jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)