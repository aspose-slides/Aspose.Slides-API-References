---
title: Yield()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια εργασία με δυνατότητα αναμονής που επιστρέφει ασύγχρονα στον τρέχοντα περιβάλλον όταν ανακληθεί.
type: docs
weight: 222
url: /el/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() συνάρτηση


Δημιουργεί μια εργασία με δυνατότητα αναμονής που επιστρέφει ασύγχρονα στον τρέχοντα περιβάλλον όταν ανακληθεί.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Τιμή Επιστροφής

Ένα YieldAwaitable που μπορεί να ανακληθεί για να παραχωρήσει τον έλεγχο.
## Παρατηρήσεις



Αυτή η μέθοδος είναι χρήσιμη για την ανάγκαση μιας ασύγχρονης μεθόδου να παραχωρήσει τον έλεγχο, επιτρέποντας την επεξεργασία άλλων εκκρεμών εργασιών πριν από τη συνέχιση. 
## Δείτε επίσης

* Κλάση [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)