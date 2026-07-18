---
title: ThreadPoolImpl
second_title: Aspose.Slides για C++ Αναφορά API
description: Εσωτερικά δεδομένα της δεύσας νημάτων. Αυτός είναι ένας τύπος singleton με διαχείριση μνήμης που γίνεται μέσω των συναρτήσεων πρόσβασης. Δεν πρέπει ποτέ να δημιουργείτε περιπτώσεις του απευθείας.
type: docs
weight: 235
url: /el/system.threading/threadpoolimpl/
---
## ThreadPoolImpl κλάση


[Thread](../thread/) εσωτερικά δεδομένα του pool. Αυτός είναι ένας τύπος singleton με διαχείριση μνήμης που γίνεται μέσω των λειτουργιών πρόσβασης(s). Δε πρέπει ποτέ να δημιουργείτε περιπτώσεις του άμεσα.

```cpp
class ThreadPoolImpl
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Επιστρέφει τον αριθμό των διαθέσιμων νημάτων. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Επιστρέφει την κατάσταση αρχικοποίησης του singleton. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Επιστρέφει το μέγιστο αριθμό ταυτόχρονων νημάτων. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Επιστρέφει το ελάχιστο αριθμό νημάτων που δημιουργούνται από τη δεύσα. |
| void [JoinAll](./joinall/)() | Συμμετέχει σε όλα τα ιδιόκτητα νήματα. Περιμένει απεριόριστα. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Προσθέτει στοιχείο εργασίας στην ουρά. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Ορίζει τον αριθμό των νημάτων που ανήκουν στη δεύσα. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Ορίζει το ελάχιστο αριθμό νημάτων που ανήκουν στη δεύσα. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Κατασκευαστής. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Καταστροφέας. Συμμετέχει σε όλα τα νήματα εάν δεν έχουν τερματιστεί ακόμη. |
## Δείτε επίσης

* Χώρος ονομάτων [System::Threading](../)
* Βιβλιοθήκη [Aspose.Slides](../../)