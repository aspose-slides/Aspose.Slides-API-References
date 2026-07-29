---
title: Cancel()
second_title: Aspose.Slides för C++ API-referens
description: Kommunicerar en begäran om avbrytning.
type: docs
weight: 40
url: /sv/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() metod


Kommunicerar en begäran om avbrytning.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Anmärkningar



Alla registrerade återanrop kommer att anropas. 

Efterföljande anrop till [get_IsCancellationRequested()](../get_iscancellationrequested/) kommer att returnera true. 

Återanrop körs synkront under detta anrop. 

## Se också

* Klass [CancellationTokenSource](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)