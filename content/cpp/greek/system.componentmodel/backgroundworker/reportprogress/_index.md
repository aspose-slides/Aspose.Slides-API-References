---
title: ReportProgress()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Ενεργοποιεί το συμβάν System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /el/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) μέθοδος

Ενεργοποιεί το συμβάν **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| percentProgress | int | Το ποσοστό, από 0 έως 100, της λειτουργίας στο παρασκήνιο που έχει ολοκληρωθεί. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) μέθοδος

Ενεργοποιεί το συμβάν **System::ComponentModel::BackgroundWorker::ProgressChanged** με αντικείμενο userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| percentProgress | int | Το ποσοστό, από 0 έως 100, της λειτουργίας στο παρασκήνιο που έχει ολοκληρωθεί. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Το αντικείμενο κατάστασης που μεταβιβάζεται στο System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [BackgroundWorker](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)