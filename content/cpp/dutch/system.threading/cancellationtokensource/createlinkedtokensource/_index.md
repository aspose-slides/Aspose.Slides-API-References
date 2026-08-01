---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een gekoppelde tokenbron die wordt geannuleerd wanneer een van de opgegeven tokens wordt geannuleerd.
type: docs
weight: 66
url: /nl/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) methode

Maakt een gekoppelde tokenbron die wordt geannuleerd wanneer een van de opgegeven tokens wordt geannuleerd.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Eerste annulerings-token om te monitoren. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Tweede annulerings-token om te monitoren. |

### Retourwaarde

Nieuwe tokenbron die wordt geannuleerd wanneer een van de invoertokens wordt geannuleerd.

## Opmerkingen

De geretourneerde bron wordt onmiddellijk geannuleerd als een van de invoertokens al geannuleerd is.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [CancellationTokenSource](../)
* Klasse [CancellationToken](../../cancellationtoken/)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)