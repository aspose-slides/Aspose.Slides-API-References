---
title: ForEach()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εκτελεί μια λειτουργία foreach σε ένα IEnumerable, στην οποία οι επαναλήψεις μπορούν να εκτελεστούν παράλληλα.
type: docs
weight: 1
url: /el/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method

Εκτελεί μια λειτουργία foreach σε ένα IEnumerable, στην οποία οι επαναλήψεις μπορούν να εκτελεστούν παράλληλα.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TSource | Ο τύπος των δεδομένων στην πηγή. |

### Παράμετρα

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Μια πηγή δεδομένων που μπορεί να επαναληφθεί. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Ένα αντικείμενο που ρυθμίζει τη συμπεριφορά αυτής της λειτουργίας. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Ο delegate που καλείται μία φορά ανά επανάληψη. |

### Τιμή επιστροφής

Μια [ParallelLoopResult](../../parallelloopresult/) δομή που περιέχει πληροφορίες για το ποιο τμήμα του βρόχου ολοκληρώθηκε.

## Παρατηρήσεις

Αυτή η μέθοδος κατανέμει το πηγαίο σύνολο δεδομένων και εκτελεί τον delegate του σώματος σε πολλαπλά νήματα ταυτόχρονα.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method

Εκτελεί μια λειτουργία foreach σε ένα IEnumerable, στην οποία οι επαναλήψεις μπορούν να εκτελεσθούν παράλληλα.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TSource | Ο τύπος των δεδομένων στην πηγή. |

### Παράμετρα

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Μια πηγή δεδομένων που μπορεί να επαναληφθεί. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Ο delegate που καλείται μία φορά ανά επανάληψη. |

### Τιμή επιστροφής

Μια [ParallelLoopResult](../../parallelloopresult/) δομή που περιέχει πληροφορίες για το ποιο τμήμα του βρόχου ολοκληρώθηκε.

## Παρατηρήσεις

Χρησιμοποιεί το προεπιλεγμένο [ParallelOptions](../../paralleloptions/) με απεριόριστο παράλληλο επίπεδο και χωρίς ακύρωση.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Κλάση [ParallelLoopResult](../../parallelloopresult/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Κλάση [ParallelOptions](../../paralleloptions/)
* Κλάση [Parallel](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)