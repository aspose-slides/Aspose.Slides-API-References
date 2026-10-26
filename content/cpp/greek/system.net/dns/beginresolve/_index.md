---
title: BeginResolve()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας εμφάνισης της κλάσης IPHostEntry-class χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή.
type: docs
weight: 157
url: /el/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία μιας νέας εμφάνισης της κλάσης IPHostEntry χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Ένα όνομα κεντρικού υπολογιστή που χρησιμοποιείται για τη δημιουργία μιας νέας εμφάνισης της κλάσης [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια συνάρτηση επανάκλησης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκινημένη ασύγχρονη λειτουργία.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [String](../../../system/string/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Dns](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)