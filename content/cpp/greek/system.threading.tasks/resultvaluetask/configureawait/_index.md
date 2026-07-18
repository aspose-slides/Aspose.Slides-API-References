---
title: ConfigureAwait()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ρυθμίζει έναν awaiter για αυτήν τη εργασία.
type: docs
weight: 92
url: /el/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const μέθοδος

Ρυθμίζει έναν awaiter για αυτήν τη εργασία.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true για να προσπαθήσει να μεταφέρει τη συνέχιση πίσω στο αρχικό context που είχε ληφθεί· διαφορετικά, false. |

### Τιμή Επιστροφής

ConfiguredResultValueTaskAwaitable<T> Ένα αντικείμενο που ρυθμίζει πώς συμπεριφέρονται οι awaiters για αυτήν τη εργασία.

## Δείτε επίσης

* Κλάση [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Κλάση [ResultValueTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)