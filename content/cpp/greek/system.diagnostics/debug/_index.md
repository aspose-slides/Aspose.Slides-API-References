---
title: Debug
second_title: Aspose.Slides για C++ API Αναφορά
description: Συλλογή μεθόδων αποσφαλμάτωσης που επιτρέπουν την αποστολή πληροφοριών αποσφαλμάτωσης σε εγγεγραμμένους ακροατές. Όλες οι συναρτήσεις εξόδου λειτουργούν μόνο στο Debug. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες αντικειμένων. Ποτέ δεν πρέπει να δημιουργείτε παραδείγματα του με κανέναν τρόπο.
type: docs
weight: 105
url: /el/system.diagnostics/debug/
---
## Δομή αποσφαλμάτωσης


Συλλογή μεθόδων αποσφαλμάτωσης που επιτρέπουν την αποστολή πληροφοριών αποσφαλμάτωσης σε εγγεγραμμένους ακροατές. Όλες οι συναρτήσεις εξόδου λειτουργούν μόνο στο [Debug](./). Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες αντικειμένων. Δεν πρέπει ποτέ να δημιουργείτε παραδείγματα του με οποιονδήποτε τρόπο.

```cpp
class Debug
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Επικυρώνει την κατάσταση και στέλνει πληροφορίες σε περίπτωση αποτυχίας. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Επικυρώνει την κατάσταση και στέλνει πληροφορίες σε περίπτωση αποτυχίας. |
| static void [Assert](./assert/)(**bool**, const char *) | Επικυρώνει την κατάσταση και στέλνει πληροφορίες σε περίπτωση αποτυχίας. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Επικυρώνει την κατάσταση και στέλνει πληροφορίες σε περίπτωση αποτυχίας. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Στέλνει μήνυμα αποτυχίας. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Πρόσβαση στη στατική λίστα ακροατών. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Εκτυπώνει μήνυμα στη διεπαφή αποσφαλμάτωσης. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Εκτυπώνει μήνυμα στη διεπαφή αποσφαλμάτωσης. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Γράφει συμβολοσειρά στη διεπαφή αποσφαλμάτωσης. |
| static void [Write](./write/)(const char_t *) | Γράφει συμβολοσειρά στη διεπαφή αποσφαλμάτωσης. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Γράφει συμβολοσειρά στη διεπαφή αποσφαλμάτωσης εάν μια κατάσταση είναι αληθής. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Γράφει γραμμή στη διεπαφή αποσφαλμάτωσης. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Γράφει γραμμή στη διεπαφή αποσφαλμάτωσης. |
| static void [WriteLine](./writeline/)(const char_t *) | Γράφει γραμμή στη διεπαφή αποσφαλμάτωσης. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Γράφει γραμμή στη διεπαφή αποσφαλμάτωσης. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Γράφει γραμμή στη διεπαφή αποσφαλμάτωσης εάν μια κατάσταση είναι αληθής. |
## Δείτε επίσης

* Χώρος ονομάτων [System::Diagnostics](../)
* Βιβλιοθήκη [Aspose.Slides](../../)