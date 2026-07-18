---
title: ThreadPool
second_title: Αναφορά API Aspose.Slides για C++
description: API πισίνας νημάτων που επιτρέπει την τοποθέτηση εργασιών στην ουρά για ανάγνωση από ομάδα νημάτων εργασίας. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες παραδείγματος. Δεν πρέπει ποτέ να δημιουργείτε παραδείγματα του με κανέναν τρόπο.
type: docs
weight: 222
url: /el/system.threading/threadpool/
---
## ThreadPool κλάση

[Thread](../thread/) pool API που επιτρέπει την καταχώριση εργασιών στην ουρά για ανάγνωση από μια ομάδα νήματων εργασίας. Αυτό είναι ένας στατικός τύπος χωρίς υπηρεσίες παραδείγματος. Δεν πρέπει ποτέ να δημιουργήσετε παραδείγματα του με κανέναν τρόπο.

```cpp
class ThreadPool : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμα και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμα και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Για εσωτερική χρήση μόνο. |
| static void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Παίρνει τον αριθμό των διαθέσιμων νημάτων. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| static [ThreadPoolImpl](../threadpoolimpl/)\& [GetInstance](./getinstance/)() | Παράδειγμα υλοποίησης που κρατά τη λίστα των εργασιών και άλλες παραμέτρους. |
| static void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Παίρνει τον μέγιστο αριθμό ταυτόχρονων νημάτων. |
| static void [GetMinThreads](./getminthreads/)(int\&, int\&) | Παίρνει τον ελάχιστο αριθμό νημάτων που δημιουργούνται από την ομάδα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα παράδειγμα τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| static void [JoinAllThreads](./joinallthreads/)() | Συνδέει όλα τα αποκτημένα νήματα. Περιμένει απεριόριστα. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή lock() της C# για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| void [operator=](./operator_equal/)(const [ThreadPool](./)\&) | Δεν γίνεται αντιγραφή. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/)) | Τοποθετεί στοιχείο εργασίας στην ουρά που υπάρχει με κλήση επιστροφής χωρίς παράμετρο. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Τοποθετεί στοιχείο εργασίας στην ουρά που υπάρχει με κλήση επιστροφής χωρίς παράμετρο. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| static **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Ορίζει τον αριθμό των νημάτων που κατέχει η ομάδα. |
| static **bool** [SetMinThreads](./setminthreads/)(int, int) | Ορίζει τον ελάχιστο αριθμό νημάτων που κατέχει η ομάδα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως ασθενή δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε ασθενή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [ThreadPool](./threadpool/)(const [ThreadPool](./)\&) | Δεν γίνεται αντιγραφή. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της εντολής lock() της C#. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον ασθενή μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον ασθενή μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Σχόλια

```cpp
#include "system/threading/thread_pool.h"
#include "system/threading/thread.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>
#include <mutex>
#include <string>
#include <thread>

const std::string &BooleanToString(bool value)
{
  static const std::string True = "True";
  static const std::string False = "False";

  return value ? True : False;
}

int main()
{
  using namespace System::Threading;
  std::mutex m;

  const auto threadsCount = std::thread::hardware_concurrency();

  for (unsigned int i = 0; i < threadsCount; ++i)
  {
    ThreadPool::QueueUserWorkItem([&m](System::SharedPtr<System::Object> object) -> void {
      auto thread = Thread::get_CurrentThread();
      m.lock();
      std::cout << "Background: " << BooleanToString(thread->get_IsBackground()) <<
        ", Thread pool: " << BooleanToString(thread->get_IsThreadPoolThread()) <<
        ", Thread ID: " << thread->get_ManagedThreadId() << std::endl;
      m.unlock();
    });
  }

  ThreadPool::JoinAllThreads();

  return 0;
}
/*
Αυτή η παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 1
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 3
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 5
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 6
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 9
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 1
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 7
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 2
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 4
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 3
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 12
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 8
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 5
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 6
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 16
Υπόβαθρο: Αληθές, Πισίνα νημάτων: Αληθές, Αναγνωριστικό νήματος: 11
*/
```

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Ονομαχώρος [System::Threading](../)
* Βιβλιοθήκη [Aspose.Slides](../../)