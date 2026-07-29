---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en länkad tokenkälla som avbryts när någon av de angivna tokenarna avbryts.
type: docs
weight: 66
url: /sv/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method

Skapar en länkad tokenkälla som avbryts när någon av de tillhandahållna tokenarna avbryts.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Första avbokningstoken att övervaka. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Andra avbokningstoken att övervaka. |

### Returvärde

Ny tokenkälla som avbryts när någon av ingångstokenarna avbryts.

## Anmärkningar

Den returnerade källan kommer omedelbart att avbrytas om någon av ingångstokenarna redan är avbruten. 

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [CancellationTokenSource](../)
* Klass [CancellationToken](../../cancellationtoken/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)