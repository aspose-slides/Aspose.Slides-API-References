---
title: Cancel()
second_title: Aspose.Slides für C++ API-Referenz
description: Teilt eine Anforderung für den Abbruch mit.
type: docs
weight: 40
url: /de/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() Methode


Teilt eine Anforderung für den Abbruch mit.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Hinweise



Alle registrierten Rückrufe werden aufgerufen. 

Nachfolgende Aufrufe von [get_IsCancellationRequested()](../get_iscancellationrequested/) geben true zurück. 

Rückrufe werden synchron während dieses Aufrufs ausgeführt. 

## Siehe auch

* Klasse [CancellationTokenSource](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)