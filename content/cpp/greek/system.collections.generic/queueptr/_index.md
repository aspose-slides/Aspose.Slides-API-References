---
title: QueuePtr
second_title: Aspose.Slides για C++ Αναφορά API
description: Δείκτης ουράς. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλου αντικειμένου. Θα πρέπει να εκχωρείται στο στοίβο και να περνάει σε συναρτήσεις είτε με τιμή είτε με σταθερή αναφορά.
type: docs
weight: 482
url: /el/system.collections.generic/queueptr/
---
## QueuePtr κλάση

[Queue](../queue/) δείκτης. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να εκχωρείται στο στοίβο και να περνάει σε συναρτήσεις είτε με τιμή είτε με σταθερή αναφορά.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη στον ίδιο του τον τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη σε βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη σε παράγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη σε παράγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../../system/smartptr/cend/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Λαμβάνει το αντικείμενο που δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Λαμβάνει τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Λαμβάνει το αντικείμενο που δείχνει, αλλά επιβεβαιώνει ότι ο δείκτης βρίσκεται σε κοινόχρηστη λειτουργία. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Λαμβάνει τον αριθμό των κοινόχρηστων δεικτών που υπάρχουν στο αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Επιβεβαιώνει ότι ο τρέχων δείκτης βρίσκεται σε κοινόχρηστη λειτουργία. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί τη [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο που δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Λαμβάνει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Λαμβάνει το αντικείμενο που δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με τη [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Λαμβάνει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Λαμβάνει το αντικείμενο που δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με τη [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο στο οποίο δείχνει είναι συγκεκριμένου τύπου ή του υποτύπου του. Ακολουθεί τη σημασιολογία 'is' της C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει εάν ο δείκτης δείχνει σε άλλο αντικείμενο από αυτό που κατέχει (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει εάν ο δείκτης βρίσκεται σε κοινόχρηστη λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει εάν ο δείκτης βρίσκεται σε αδύναμη λειτουργία. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει εάν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει εάν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Λαμβάνει αναφορά στο αντικείμενο στο οποίο δείχνει. Επιβεβαιώνει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία σύγκρισης μικρότερου για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία σύγκρισης μικρότερου για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Αναθέτει με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται μη χρησιμοποιήσιμο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αναθέτει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αναθέτει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Εκτελεί τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει εάν ο δείκτης δείχνει σε nullptr. |
| [QueuePtr](./queueptr/)() | Δημιουργεί δείκτη null. |
| [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Δημιουργεί δείκτη σε συγκεκριμένη σειρά. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί την εναλλαξία (δημιουργημένη από κατασκευαστή aliasing) από το δείκτη, διασφαλίζει ότι διαχειρίζεται (αν είναι κοινόχρηστο) ή παρακολουθεί (αν είναι αδύναμο) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο που δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφοράς του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο που δείχνει (εάν υπάρχει). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) null-pointer της απαιτούμενης λειτουργίας. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο συγκεκριμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί τη μετατροπή τύπου αν επιτρέπεται. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Στην ουσία, ανταλλάσσει δύο δείκτες, εφόσον και οι δύο είναι της ίδιας λειτουργίας. Το x μπορεί να γίνει μη χρησιμοποιήσιμο μετά την κλήση. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο εάν στην C# υπάρχει μετατροπή τύπου πίνακα που δεν υποστηρίζεται στην C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για τη μετάφραση ορισμένων κατασκευών κώδικα C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται τις πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά κρατά έναν άσχετο και αδιαχειρίσιμο δείκτη p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για τη λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφοράς του αντικειμένου που δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)