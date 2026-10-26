---
title: BeginGetHostByName()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου αντικειμένου IPHostEntry-class χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή.
type: docs
weight: 53
url: /el/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος


Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-class αντικειμένου χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Ένα όνομα κεντρικού υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μία κλήση επιστροφής που καλείται όταν ολοκληρωθεί η λειτουργία. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Return Value

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την ξεκινόμενη ασύγχρονη λειτουργία.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Τάξη [IAsyncResult](../../../system/iasyncresult/)
* Τάξη [String](../../../system/string/)
* Τάξη [Object](../../../system/object/)
* Τάξη [Dns](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)