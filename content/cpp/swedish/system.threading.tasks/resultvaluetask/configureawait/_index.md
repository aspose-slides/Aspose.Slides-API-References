---
title: ConfigureAwait()
second_title: Aspose.Slides för C++ API-referens
description: Konfigurerar en väntare för den här uppgiften.
type: docs
weight: 92
url: /sv/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const metod

Konfigurerar en väntare för den här uppgiften.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true för att försöka överföra fortsättningen tillbaka till den ursprungliga kontexten som fångats; annars false. |

### Returvärde

ConfiguredResultValueTaskAwaitable<T> Ett objekt som konfigurerar hur väntare beter sig för den här uppgiften.

## Se även

* Klass [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Klass [ResultValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)