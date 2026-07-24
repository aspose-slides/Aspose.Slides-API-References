---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine verknüpfte Token-Quelle, die abgebrochen wird, wenn einer der bereitgestellten Token abgebrochen wird.
type: docs
weight: 66
url: /de/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) Methode

Creates a linked token source that cancels when any of the provided tokens cancel.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Erster zu überwachender Abbruch-Token. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Zweiter zu überwachender Abbruch-Token. |

### Rückgabewert

Neue Token-Quelle, die abgebrochen wird, wenn einer der Eingabe-Token abgebrochen wird.

## Hinweise

Die zurückgegebene Quelle wird sofort abgebrochen, wenn einer der Eingabe-Token bereits abgebrochen ist. 

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [CancellationTokenSource](../)
* Klasse [CancellationToken](../../cancellationtoken/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)