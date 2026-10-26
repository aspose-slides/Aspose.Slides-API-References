---
title: Monitor
second_title: Aspose.Slides για C++ Αναφορά API
description: Η κλάση Monitor παρέχει έναν μηχανισμό που συγχρονίζει την πρόσβαση σε αντικείμενα.
type: docs
weight: 157
url: /el/system.threading/monitor/
---
## Monitor κλάση

Κλάση [Monitor](./) παρέχει έναν μηχανισμό που συγχρονίζει την πρόσβαση σε αντικείμενα.

```cpp
class Monitor : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Αποκτά αποκλειστικό κλείδωμα σε ένα καθορισμένο αντικείμενο. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Αποκτά αποκλειστικό κλείδωμα στο καθορισμένο αντικείμενο και ατομικά ορίζει μια τιμή που υποδεικνύει αν το κλείδωμα ελήφθη. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Απελευθερώνει ένα αποκλειστικό κλείδωμα στο καθορισμένο αντικείμενο. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Καθορίζει αν το τρέχον νήμα κατέχει το κλείδωμα στο καθορισμένο αντικείμενο. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Ειδοποιεί ένα νήμα στην ουρά αναμονής για αλλαγή στην κατάσταση του κλειδωμένου αντικειμένου. Δεν έχει υλοποιηθεί. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Ειδοποιεί όλα τα νήματα που περιμένουν για αλλαγή στην κατάσταση του αντικειμένου. Δεν έχει υλοποιηθεί. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα του προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Προσπάθεια απόκτησης αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν έχει υλοποιηθεί. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Προσπάθεια απόκτησης αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο και ατομικά ορίζει μια τιμή που δείχνει αν το κλείδωμα ελήφθη. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Προσπάθεια, για τον καθορισμένο αριθμό χιλιοστών του δευτερολέπτου, απόκτησης αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν έχει υλοποιηθεί. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Προσπάθεια, για το καθορισμένο χρονικό διάστημα, απόκτησης αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν έχει υλοποιηθεί. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | Προσπάθεια, για το καθορισμένο χρονικό διάστημα, απόκτησης αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο, και ατομικά ορίζει μια τιμή που υποδεικνύει αν το κλείδωμα ελήφθη. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | Προσπάθεια, για το καθορισμένο χρονικό διάστημα, απόκτησης αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο, και ατομικά ορίζει μια τιμή που υποδεικνύει αν το κλείδωμα ελήφθη. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | Απελευθερώνει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επαναλάβει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Προαιρετικά, εξέρχεται από το τομέα συγχρονισμού για το συγχρονισμένο περιβάλλον πριν από την αναμονή και επαναλαμβάνει την είσοδο στο τομέα μετά. Δεν έχει υλοποιηθεί. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | Απελευθερώνει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επαναλάβει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Προαιρετικά, εξέρχεται από το τομέα συγχρονισμού για το συγχρονισμένο περιβάλλον πριν από την αναμονή και επαναλαμβάνει την είσοδο στο τομέα μετά. Δεν έχει υλοποιηθεί. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Απελευθερώνει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επαναλάβει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Δεν έχει υλοποιηθεί. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Απελευθερώνει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επαναλάβει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Δεν έχει υλοποιηθεί. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Απελευθερώνει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επαναλάβει το κλείδωμα. Δεν έχει υλοποιηθεί. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Αριθμός νημάτων: 3
Νήμα 0: 1
Νήμα 0: 2
Νήμα 0: 3
Νήμα 0: 4
Νήμα 0: 5
Νήμα 1: 1
Νήμα 1: 2
Νήμα 1: 3
Νήμα 1: 4
Νήμα 1: 5
Νήμα 2: 1
Νήμα 2: 2
Νήμα 2: 3
Νήμα 2: 4
Νήμα 2: 5
*/
```

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Threading](../)
* Βιβλιοθήκη [Aspose.Slides](../../)