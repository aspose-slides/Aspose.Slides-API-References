---
title: ConfigureAwait()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαμορφώνει έναν awaiter για αυτήν την εργασία.
type: docs
weight: 79
url: /el/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const μέθοδος

Διαμορφώνει έναν awaiter για αυτήν την εργασία.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true για να προσπαθήσει να μεταφέρει τη συνέχεια πίσω στο αρχικό καταγεγραμμένο πλαίσιο· διαφορετικά, false. |

### Τιμή Επιστροφής

ConfiguredValueTaskAwaitable Ένα αντικείμενο που διαμορφώνει πώς οι awaiters συμπεριφέρονται για αυτήν την εργασία.

## Δείτε επίσης

* Κλάση [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Κλάση [ValueTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)