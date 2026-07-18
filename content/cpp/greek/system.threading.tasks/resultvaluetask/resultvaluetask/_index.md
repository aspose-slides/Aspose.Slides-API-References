---
title: ResultValueTask()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα κενό, μη αρχικοποιημένο ResultValueTask.
type: docs
weight: 1
url: /el/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() κατασκευαστής


Δημιουργεί ένα κενό, μη αρχικοποιημένο [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Σχόλια



Η εργασία δεν έχει ολοκληρωθεί και δεν περιέχει αποτέλεσμα. Η προσπάθεια απόκτησης του αποτελέσματος θα προκαλέσει εξαίρεση. 

## ResultValueTask::ResultValueTask(const T\&) κατασκευαστής


Δημιουργεί ένα ολοκληρωμένο [ResultValueTask](../) με το καθορισμένο αποτέλεσμα.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | const T\& | Η τιμή αποτελέσματος που θα περιτυλιχθεί σε μια ολοκληρωμένη εργασία. |
## Σχόλια



Αυτό δημιουργεί μια εργασία που ολοκληρώθηκε επιτυχώς και επιστρέφει αμέσως την τιμή. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) κατασκευαστής


Δημιουργεί ένα [ResultValueTask](../) από έναν κοινόχρηστο δείκτη προς ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Η εργασία προς περιτύλιξη. Μπορεί να είναι null για κενή εργασία. |
## Σχόλια



Το [ResultValueTask](../) θα αντιπροσωπεύει την κατάσταση και το αποτέλεσμα της παρεχόμενης εργασίας. 

## Δείτε επίσης

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Κλάση [ResultValueTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)