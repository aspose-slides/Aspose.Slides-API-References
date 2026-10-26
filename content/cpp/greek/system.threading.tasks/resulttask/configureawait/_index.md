---
title: ConfigureAwait()
second_title: Aspose.Slides για C++ API Reference
description: Διαμορφώνει πώς τα await σε αυτήν τη result task θα πρέπει να συμπεριφέρονται σχετικά με τη σύλληψη του context.
type: docs
weight: 27
url: /el/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const μέθοδος

Διαμορφώνει τον τρόπο με τον οποίο τα await σε αυτήν τη result task θα πρέπει να συμπεριφέρονται σχετικά με τη σύλληψη του context.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Εάν πρέπει να συνεχιστεί στο captured context |

### Τιμή επιστροφής

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Ένα διαμορφωμένο awaitable για το αποτέλεσμα

## Παρατηρήσεις

Αυτό επιτρέπει λεπτομερή έλεγχο της ροής του context για τα μοτίβα async/await

## Δείτε επίσης

* Κλάση [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Κλάση [ResultTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)