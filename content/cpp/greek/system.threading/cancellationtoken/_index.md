---
title: CancellationToken
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαδίδει ειδοποίηση ότι οι λειτουργίες πρέπει να ακυρωθούν. Αυτή η κλάση παρέχει έναν μηχανισμό συνεργατικής ακύρωσης μεταξύ νημάτων, επιτρέποντας σε ένα νήμα να ειδοποιεί τα άλλα ότι μια λειτουργία πρέπει να ακυρωθεί.
type: docs
weight: 14
url: /el/system.threading/cancellationtoken/
---
## Κλάση CancellationToken


Διαδίδει ειδοποίηση ότι οι λειτουργίες πρέπει να ακυρωθούν. Αυτή η κλάση παρέχει έναν μηχανισμό συνεργατικής ακύρωσης μεταξύ νημάτων, επιτρέποντας σε ένα νήμα να ειδοποιεί τα άλλα ότι μια λειτουργία πρέπει να ακυρωθεί.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Προεπιλεγμένος κατασκευαστής. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Επιστρέφει αν αυτό το διακριτικό μπορεί να βρίσκεται στην κατάσταση ακύρωσης. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Επιστρέφει αν έχει ζητηθεί η ακύρωση για αυτό το διακριτικό. |
| static [CancellationToken](./) [get_None](./get_none/)() | Επιστρέφει μια κενή [System::Threading::CancellationToken](./) τιμή. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Καταχωρεί μια κλήση που θα εκτελεστεί όταν ζητηθεί η ακύρωση. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Ρίχνει μια OperationCanceledException εάν έχει ζητηθεί η ακύρωση. |
## Παρατηρήσεις



Ένα [CancellationToken](./) μπορεί να ακυρωθεί μόνο μέσω του συσχετισμένου [CancellationTokenSource](../cancellationtokensource/) του. 

## Δείτε επίσης

* Χώρος ονομάτων [System::Threading](../)
* Βιβλιοθήκη [Aspose.Slides](../../)