---
title: ConfigureAwait()
second_title: Aspose.Slides för C++ API-referens
description: Konfigurerar hur await-operationer på detta result task ska bete sig avseende kontextfångst.
type: docs
weight: 27
url: /sv/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const metod


Konfigurerar hur await-operationer på detta resulttask ska bete sig avseende kontextfångst.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Anger om fortsättningen ska ske på den fångade kontexten |

### Returvärde

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> En konfigurerad awaitable för resultatet
## Anmärkningar



Detta möjliggör finjusterad kontroll över kontextflödet för async/await-mönster 

## Se även

* Klass [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Klass [ResultTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)