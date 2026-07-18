---
title: Parallel
second_title: Αναφορά API του Aspose.Slides για C++
description: Παρέχει υποστήριξη για παράλληλους βρόχους και περιοχές.
type: docs
weight: 1
url: /el/system.threading.tasks/parallel/
---
## Κλάση Parallel

Παρέχει υποστήριξη για παράλληλους βρόχους και περιοχές.

```cpp
class Parallel
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Εκτελεί μια λειτουργία foreach σε ένα IEnumerable, στην οποία οι επαναλήψεις ενδέχεται να εκτελεστούν παράλληλα. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Εκτελεί μια λειτουργία foreach σε ένα IEnumerable, στην οποία οι επαναλήψεις ενδέχεται να εκτελεστούν παράλληλα. |

## Παρατηρήσεις

Αυτή η κλάση παρέχει μεθόδους για παράλληλη εκτέλεση βρόχων και λειτουργιών.

## Δείτε επίσης

* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)