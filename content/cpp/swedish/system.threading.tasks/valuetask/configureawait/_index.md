---
title: ConfigureAwait()
second_title: Aspose.Slides för C++ API-referens
description: Konfigurerar en väntare för den här uppgiften.
type: docs
weight: 79
url: /sv/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const metod


Konfigurerar en väntare för den här uppgiften.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true för att försöka skicka vidare fortsättningen tillbaka till den ursprungliga kontexten som fångats; annars false. |

### Returvärde

ConfiguredValueTaskAwaitable Ett objekt som konfigurerar hur väntare beter sig för den här uppgiften.

## Se även

* Klass [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Klass [ValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)