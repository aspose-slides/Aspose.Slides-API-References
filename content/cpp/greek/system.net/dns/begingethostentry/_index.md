---
title: BeginGetHostEntry()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εκκινεί μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας παρουσίας κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP.
type: docs
weight: 105
url: /el/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Εκκινεί μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας παρουσίας κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Η συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση-επιστροφή που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκινηθείσα ασύγχρονη λειτουργία.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Εκκινεί μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας παρουσίας κλάσης IPHostEntry χρησιμοποιώντας την καθορισμένη διεύθυνση IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Η διεύθυνση IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση-επιστροφή που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκινηθείσα ασύγχρονη λειτουργία.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [String](../../../system/string/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Dns](../)
* Κλάση [IPAddress](../../ipaddress/)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)