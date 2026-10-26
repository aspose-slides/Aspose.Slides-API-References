---
title: WebExceptionStatus
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Απαριθμεί τους κωδικούς κατάστασης της κλάσης WebException.
type: docs
weight: 651
url: /el/system.net/webexceptionstatus/
---
## WebExceptionStatus enum


Enumerates the status codes of the WebException class.

```cpp
enum class WebExceptionStatus
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Success | 0 | Δεν προέκυψαν σφάλματα. |
| NameResolutionFailure | 1 | Η υπηρεσία επίλυσης ονομάτων δεν μπόρεσε να επιλύσει το όνομα κεντρικού υπολογιστή. |
| ConnectFailure | 2 | Δεν ήταν δυνατή η επικοινωνία με το απομακρυσμένο σημείο υπηρεσίας στο επίπεδο μεταφοράς. |
| ReceiveFailure | 3 | Δεν λήφθηκε πλήρης απόκριση από τον απομακρυσμένο διακομιστή. |
| SendFailure | 4 | Δεν μπόρεσε να αποσταλεί πλήρης αίτηση στον απομακρυσμένο διακομιστή. |
| PipelineFailure | 5 | Η αίτηση ήταν pipeline και η σύνδεση κλείστηκε πριν ληφθεί η απόκριση. |
| RequestCanceled | 6 | Η αίτηση ακυρώθηκε ή προέκυψε σφάλμα που δεν μπορεί να ταξινομηθεί. |
| ProtocolError | 7 | Η ληφθείσα απόκριση από τον διακομιστή ήταν πλήρης αλλά υποδείκνυε σφάλμα επιπέδου πρωτοκόλλου. |
| ConnectionClosed | 8 | Η σύνδεση έκλεισε πρόωρα. |
| TrustFailure | 9 | Δεν μπόρεσε να επικυρωθεί το πιστοποιητικό του διακομιστή. |
| SecureChannelFailure | 10 | Παρουσιάστηκε σφάλμα κατά τη δημιουργία σύνδεσης με χρήση SSL. |
| ServerProtocolViolation | 11 | Η απόκριση του διακομιστή δεν ήταν έγκυρη απόκριση HTTP. |
| KeepAliveFailure | 12 | Η σύνδεση για μια αίτηση που καθορίζει την κεφαλίδα 'Keep-Alive' έκλεισε απροσδόκητα. |
| Pending | 13 | Μία εσωτερική ασύγχρονη αίτηση βρίσκεται σε εκκρεμότητα. |
| Timeout | 14 | Δεν λήφθηκε απόκριση κατά τη διάρκεια του χρονικού ορίου για μία αίτηση. |
| ProxyNameResolutionFailure | 15 | Η υπηρεσία επίλυσης ονομάτων δεν μπόρεσε να επιλύσει το όνομα κεντρικού υπολογιστή του διαμεσολαβητή. |
| UnknownError | 16 | Παρουσιάστηκε εξαίρεση άγνωστου τύπου. |
| MessageLengthLimitExceeded | 17 | Λήφθηκε μήνυμα που υπερβαίνει το καθορισμένο όριο. |
| CacheEntryNotFound | 18 | Η καθορισμένη καταχώρηση στη μνήμη cache δεν βρέθηκε. |
| RequestProhibitedByCachePolicy | 19 | Η αίτηση δεν επιτράπηκε από την πολιτική cache. |
| RequestProhibitedByProxy | 20 | Αυτή η αίτηση δεν επιτράπηκε από τον διαμεσολαβητή. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)