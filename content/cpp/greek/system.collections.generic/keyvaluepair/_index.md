---
title: KeyValuePair
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ζεύγος κλειδιού και τιμής. Αυτός ο τύπος πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις ως τιμή ή ως αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 378
url: /el/system.collections.generic/keyvaluepair/
---
## KeyValuePair κλάση

Ζεύγος κλειδιού και τιμής. Αυτός ο τύπος πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις ως τιμή ή ως αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../../system/smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Λαμβάνει το κλειδί. |
| const TValue\& [get_Value](./get_value/)() const | Λαμβάνει την τιμή. |
| int [GetHashCode](./gethashcode/)() const | Υπολογίζει το hash του ζεύγους κλειδιού-τιμής με XOR των hashes του κλειδιού και της τιμής. |
| **bool** [IsNull](./isnull/)() const | Πάντα επιστρέφει false. |
|  [KeyValuePair](./keyvaluepair/)() | Αρχικοποιητής κενών ζευγών κλειδιού-τιμής. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Κατασκευαστής. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Κατασκευαστής μετατροπής τύπου. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Διόρθωση για κλάσεις που κληρονομούνται από IComparer<KeyValuePair<TKey, TValue>>, δεν συγκρίνει τίποτα. |
| [String](../../system/string/) [ToString](./tostring/)() const | Μετατρέπει το ζεύγος κλειδιού-τιμής σε συμβολοσειρά. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)