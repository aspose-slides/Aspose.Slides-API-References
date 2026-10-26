---
title: FromResult()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en uppgift som har lyckats slutföras med det angivna resultatet.
type: docs
weight: 144
url: /sv/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) function


Skapar en uppgift som har lyckats slutföras med det angivna resultatet.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| TResult | Typen av uppgiftens resultat. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| result | TResult | Resultatvärdet som används för att slutföra uppgiften. |

### Returvärde

En lyckat slutförd uppgift.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)