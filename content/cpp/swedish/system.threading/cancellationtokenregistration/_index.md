---
title: CancellationTokenRegistration
second_title: Aspose.Slides för C++ API-referens
description: Representerar en registrering för en avbokningstoken-callback.
type: docs
weight: 27
url: /sv/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration klass

Representerar en registrering för en avbokningstoken-callback.

```cpp
class CancellationTokenRegistration
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Dispose](./dispose/)() | Avslutar registreringen och tar bort callbacken från den associerade [CancellationTokenSource](../cancellationtokensource/). Efter att ha anropat denna metod kommer den registrerade callbacken inte längre att anropas när den associerade [CancellationTokenSource](../cancellationtokensource/) avbokas. |
## Anmärkningar

Denna klass möjliggör avregistrering av en callback från en avbokningstoken. När den har disposeras tar den bort callbacken från den associerade [CancellationTokenSource](../cancellationtokensource/). 
Denna klass bör inte skapas direkt - den returneras av [CancellationToken](../cancellationtoken/) registreringsmetoder. 

## Se även

* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)