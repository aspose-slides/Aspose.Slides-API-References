---
title: InvokeCompletedEventArgs()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί μια νέα παρουσία.
type: docs
weight: 14
url: /el/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Οποιοδήποτε σφάλμα που προέκυψε κατά τη διάρκεια μιας ασύγχρονης λειτουργίας. |
| cancelled | **bool** | Μια τιμή που υποδεικνύει αν μια ασύγχρονη λειτουργία έχει ακυρωθεί. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Το προαιρετικό αντικείμενο κατάστασης που παρέχεται από τον χρήστη και περνιέται στην μέθοδο [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Μια συλλογή αποτελεσμάτων ασύγχρονης λειτουργίας. |

## Δείτε επίσης

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [InvokeCompletedEventArgs](../)
* Χώρος ονομάτων [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)