---
title: get_CanBeCanceled()
second_title: Aspose.Slides pro C++ API Reference
description: Zjišťuje, zda je tento token schopný být ve zrušeném stavu.
type: docs
weight: 27
url: /cs/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const metoda

Gets whether this token is capable of being in the canceled state.

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```

### Návratová hodnota

true if this token is capable of being in the canceled state; otherwise, false.
## Poznámky


Tokens created from [CancellationTokenSource](../../cancellationtokensource/) will return true, while the None token will always return false. 

## Viz také

* Třída [CancellationToken](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)