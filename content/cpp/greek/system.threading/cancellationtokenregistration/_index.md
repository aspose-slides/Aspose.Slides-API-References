---
title: CancellationTokenRegistration
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά μια εγγραφή για μια απόκριση διακριτικού ακύρωσης.
type: docs
weight: 27
url: /el/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration κλάση

Αναπαριστά μια εγγραφή για μια απόκριση διακριτικού ακύρωσης.

```cpp
class CancellationTokenRegistration
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Dispose](./dispose/)() | Καταστρέφει την εγγραφή και αφαιρεί την απόκριση από το σχετικό [CancellationTokenSource](../cancellationtokensource/). Αφού κλήσετε αυτή τη μέθοδο, η εγγεγραμμένη απόκριση δεν θα κληθεί πλέον όταν το σχετικό [CancellationTokenSource](../cancellationtokensource/) ακυρωθεί. |

## Παρατηρήσεις

Αυτή η κλάση επιτρέπει την αποεγγραφή μιας απόκρισης από ένα διακριτικό ακύρωσης. Όταν καταστρέφεται, αφαιρεί την απόκριση από το σχετικό [CancellationTokenSource](../cancellationtokensource/). 
Αυτή η κλάση δεν πρέπει να δημιουργείται άμεσα - επιστρέφεται από τις μεθόδους εγγραφής του [CancellationToken](../cancellationtoken/).

## Δείτε επίσης

* Ονομαχώρος [System::Threading](../)
* Βιβλιοθήκη [Aspose.Slides](../../)