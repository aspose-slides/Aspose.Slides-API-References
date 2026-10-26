---
title: BeginGetHostAddresses()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας παρουσίας της κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP.
type: docs
weight: 131
url: /el/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας παρουσίας της κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Μια συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση επιστροφής που θα κληθεί όταν η λειτουργία ολοκληρωθεί. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκίνητη ασύγχρονη λειτουργία.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [String](../../../system/string/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Dns](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)