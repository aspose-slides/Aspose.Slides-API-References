---
title: Cancel()
second_title: Aspose.Slides voor C++ API Referentie
description: Communiceert een verzoek tot annulering.
type: docs
weight: 40
url: /nl/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() methode


Communiceert een verzoek tot annulering.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Opmerkingen



Alle geregistreerde callbacks worden aangeroepen. 

Latere oproepen van [get_IsCancellationRequested()](../get_iscancellationrequested/) zullen true teruggeven. 

Callbacks worden synchroon uitgevoerd tijdens deze oproep. 

## Zie ook

* Klasse [CancellationTokenSource](../)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)