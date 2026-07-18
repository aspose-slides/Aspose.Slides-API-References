---
title: SmartPtr()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί αντικείμενο SmartPtr της απαιτούμενης λειτουργίας.
type: docs
weight: 1
url: /el/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) Κατασκευαστής


Δημιουργεί [SmartPtr](../) αντικείμενο της απαιτούμενης λειτουργίας.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) Κατασκευαστής


Δημιουργεί αντικείμενο [SmartPtr](../) μηδενικού δείκτη της απαιτούμενης λειτουργίας.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | std::nullptr_t | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) Κατασκευαστής


Δημιουργεί [SmartPtr](../) που δείχνει στο συγκεκριμένο αντικείμενο ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Στόχος. |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) Κατασκευαστής


Δημιουργεί αντιγραφή του αντικειμένου [SmartPtr](../). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Δείκτης προς αντιγραφή. |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) Κατασκευαστής


Δημιουργεί αντιγραφή του αντικειμένου [SmartPtr](../). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου εάν επιτρέπεται.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος του αντικειμένου που δείχνει το x. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Δείκτης προς αντιγραφή. |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) Κατασκευαστής


Δημιουργεί μετακίνηση του αντικειμένου [SmartPtr](../). Εν αποτελέσει, ανταλλάσσει δύο δείκτες εάν είναι και οι δύο στην ίδια λειτουργία. Το x μπορεί να είναι ακατάλληλο μετά την κλήση.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Δείκτης προς μετακίνηση. |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) Κατασκευαστής


Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο αν σε C# υπάρχει μετατροπή τύπου πίνακα που δεν υποστηρίζεται σε C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Y | Τύπος του πηγαίου πίνακα. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Δείκτης σε πίνακα για δημιουργία αντιγράφου, αλλά με διαφορετικό τύπο στοιχείων. |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. |

## SmartPtr::SmartPtr(const Y\&) Κατασκευαστής


Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για τη μετάφραση ορισμένων κατασκευών κώδικα C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Y | Δεσμευτικό θέσης τύπου EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) Κατασκευαστής


Δημιουργεί ένα [SmartPtr](../) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά διατηρεί έναν ανεξάρτητο και μη διαχειριζόμενο δείκτη p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Άλλο smart pointer για κοινή ιδιοκτησία με το ptr. |
| p | [Pointee_](../pointee_/) * | Δείκτης σε αντικείμενο για διαχείριση. |
| mode | [SmartPtrMode](../../smartptrmode/) | Λειτουργία δείκτη. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Αυτή η κλάση περιέχει ένα πεδίο που θα εκτυπωθεί.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Αυτή η κλάση περιέχει μια εμφάνιση της κλάσης Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Χρησιμοποιείται για την εκτύπωση μιας συμβολοσειράς από την παρουσία της κλάσης Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Εκτυπώνει τον αριθμό των shared pointers που δείχνουν στο αντικείμενο.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Δημιουργεί SharedPtr σε μια εμφάνιση της κλάσης Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Δημιουργεί SharedPtr που θα δείχνει στο πεδίο της εμφανίσεως της κλάσης Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Κάνει τον δείκτη 'bar' να δείχνει στο nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // Το bar->data εξακολουθεί να υπάρχει και ο δείκτης 'foo' είναι έγκυρος.
  PrintMessage(foo);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## Δείτε επίσης

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)