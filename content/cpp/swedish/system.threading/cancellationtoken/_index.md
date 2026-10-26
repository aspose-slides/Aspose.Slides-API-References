---
title: CancellationToken
second_title: Aspose.Slides för C++ API-referens
description: Propagerar en notifikation om att operationer bör avbrytas. Denna klass tillhandahåller en mekanism för samarbetsbaserat avbrott mellan trådar, så att en tråd kan meddela andra att en operation bör avbrytas.
type: docs
weight: 14
url: /sv/system.threading/cancellationtoken/
---
## CancellationToken klass


Propagerar en notifikation om att operationer bör avbrytas. Denna klass tillhandahåller en mekanism för samarbetsbaserat avbrott mellan trådar, så att en tråd kan meddela andra att en operation bör avbrytas.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Standardkonstruktor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Returnerar om detta token kan vara i avbrutet tillstånd. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Returnerar om avbokning har begärts för detta token. |
| static [CancellationToken](./) [get_None](./get_none/)() | Returnerar ett tomt [System::Threading::CancellationToken](./)-värde. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registrerar en återuppringning som kommer att anropas när avbokning begärs. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Kastar ett OperationCanceledException om avbokning har begärts. |
## Anmärkningar



En [CancellationToken](./) kan endast annulleras genom dess associerade [CancellationTokenSource](../cancellationtokensource/). 

## Se också

* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)