---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κατασκευαστής.
type: docs
weight: 1
url: /el/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() κατασκευαστής

Κατασκευαστής.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) κατασκευαστής

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Οποιοδήποτε σφάλμα που συνέβη κατά τη διάρκεια της ασύγχρονης λειτουργίας. |
| canceled | **bool** | Μία τιμή που υποδεικνύει εάν η ασύγχρονη λειτουργία ακυρώθηκε. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Το προαιρετικό αντικείμενο κατάστασης που παρέχεται από το χρήστη και μεταβιβάζεται στη μέθοδο [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Δείτε επίσης

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [AsyncCompletedEventArgs](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [System::ComponentModel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)