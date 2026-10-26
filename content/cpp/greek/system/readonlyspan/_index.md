---
title: ReadOnlySpan
second_title: Aspose.Slides για C++ - Αναφορά API
description: Προώθηση για χρήση εντός κλάσης Span.
type: docs
weight: 1184
url: /el/system/readonlyspan/
---
## ReadOnlySpan κλάση


Προώθηση για χρήση εντός [Span](../span/) κλάση.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span. Αυτή η κλάση παρέχει έναν τύπο-ασφαλή τρόπο εργασίας με διαδοχικές ακολουθίες αντικειμένων σε μόνο-ανάγνωστη μορφή. Μπορεί να χρησιμοποιηθεί για την περιτύλιξη πινάκων, στατικών πινάκων ή ακατέργαστων δεικτών ενώ διατηρεί τον έλεγχο ορίων. Το [ReadOnlySpan](./) δεν κατέχει τη μνήμη στην οποία δείχνει – είναι μόνο μια προβολή στην υπάρχουσα μνήμη. |
## Μέθοδοι

| Method | Description |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Δημιουργεί ένα μόνο-ανάγνωστο span από ένα κανονικό span. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Μετατρέπει έναν πίνακα σε ένα [ReadOnlySpan](./). |
## Παρατηρήσεις


Αναπαριστά μια μόνο-ανάγνωστη συνεχόμενη περιοχή αυθαίρετης μνήμης.

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)