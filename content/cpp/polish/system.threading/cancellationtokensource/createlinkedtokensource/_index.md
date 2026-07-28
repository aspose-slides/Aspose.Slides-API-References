---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy powiązane źródło tokenu, które jest anulowane, gdy którykolwiek z podanych tokenów zostanie anulowany.
type: docs
weight: 66
url: /pl/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method

Tworzy połączone źródło tokenu, które jest anulowane, gdy którykolwiek z dostarczonych tokenów zostanie anulowany.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Pierwszy token anulowania do monitorowania. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Drugi token anulowania do monitorowania. |

### Wartość zwracana

Nowe źródło tokenu, które zostanie anulowane, gdy którykolwiek z wejściowych tokenów zostanie anulowany.

## Uwagi

Zwrócone źródło zostanie natychmiast anulowane, jeśli którykolwiek z wejściowych tokenów jest już anulowany.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [CancellationTokenSource](../)
* Klasa [CancellationToken](../../cancellationtoken/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)