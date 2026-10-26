---
title: ArraySegment
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει ένα τμήμα του μονοδιάστατου πίνακα. Αυτός ο τύπος πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 40
url: /el/system/arraysegment/
---
## ArraySegment κλάση

Αντιπροσωπεύει ένα τμήμα του μονοδιάστατου πίνακα. Αυτός ο τύπος πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιήσετε την κλάση [System::SmartPtr](../smartptr/) για να διαχειριστείτε αντικείμενα αυτού του τύπου.

```cpp
template<typename T>class ArraySegment : public System::Object
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του τμήματος του πίνακα. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>) |  |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>, **int32_t**, **int32_t**) |  |
|  [ArraySegment](./arraysegment/)() |  |
|  **bool** [Equals](./equals/)([System::SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
|  **bool** [Equals](./equals/)([ArraySegment](./)\<T\>) |  |
|  virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../object/equals/). |
|  static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
|  static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
|  static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
|  virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
|  [System::ArrayPtr](../arrayptr/)\<T\> [get_Array](./get_array/)() |  |
|  **int32_t** [get_Count](./get_count/)() |  |
|  **int32_t** [get_Offset](./get_offset/)() |  |
|  Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
|  **int32_t** [GetHashCode](./gethashcode/)() const override | Αναλογία της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί το hash προσαρμοσμένων αντικειμένων. |
|  virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../object/gettype/). |
|  virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
|  void [Lock](../object/lock/)() | Υλοποιεί την εντολή C# lock() για κλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../lockcontext/). |
|  virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|   [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|   [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
|   [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
|  static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
|  static std::enable_if<\\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../object/referenceequals/)(T const\\&, T const\\&) | Συγκρίνει αντικείμενα με αναφορά. |
|  static std::enable_if<\\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../object/referenceequals/)(T const\\&, std::nullptr_t) | Σύγκριση αναφοράς αντικειμένου τύπου τιμής με nullptr. |
|  **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση string και nullptr. |
|  **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\\&, [String](../string/) const\\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση strings. |
|  int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
|  virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύνατη λειτουργία. |
|  int [SharedCount](../object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
|  [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  virtual [String](../string/) [ToString](../object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
|  static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../object/)). |
|  void [Unlock](../object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../lockcontext/). |
|  Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον μετρητή αδύνατων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον μετρητή αδύνατων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Δημιουργήστε και γεμίστε τον πίνακα.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Δημιουργήστε το τμήμα του πίνακα που περιέχει ολόκληρο τον πίνακα.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Εκτυπώστε τα στοιχεία του τμήματος του πίνακα.
  Print(fullArray);

  // Δημιουργήστε το τμήμα του πίνακα.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Εκτυπώστε τα στοιχεία του τμήματος του πίνακα.
  Print(segment);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την παρακάτω έξοδο:
First Second Third
Second Third
*/
```

## Δείτε επίσης

* Κλάση [Object](../object/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)