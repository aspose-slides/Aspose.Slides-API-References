---
title: ListPtr
second_title: Aspose.Slides για C++ API Αναφορά
description: Δείκτης λίστας με τελεστές πρόσβασης. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να εκχωρείται στη στοίβα και να περνάται σε συναρτήσεις είτε με τιμή είτε με const αναφορά.
type: docs
weight: 456
url: /el/system.collections.generic/listptr/
---
## ListPtr κλάση


[List](../list/) δείκτης με τελεστές πρόσβασης. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να εκχωρείται στη στοίβα και να περνάται σε συναρτήσεις είτε με τιμή είτε με const αναφορά.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση για τη μέθοδο [begin()](../../system/smartptr/begin/) της υποκείμενης συλλογής. Μπορεί να μεταγλωττιστεί μόνο αν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση για τη μέθοδο [begin()](../../system/smartptr/begin/) της υποκείμενης συλλογής. Μπορεί να μεταγλωττιστεί μόνο αν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη στον ίδιο του τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη σε τύπο βάσης χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση για τη μέθοδο [cbegin()](../../system/smartptr/cbegin/) της υποκείμενης συλλογής. Μπορεί να μεταγλωττιστεί μόνο αν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση για τη μέθοδο [cend()](../../system/smartptr/cend/) της υποκείμενης συλλογής. Μπορεί να μεταγλωττιστεί μόνο αν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση για τη μέθοδο [end()](../../system/smartptr/end/) της υποκείμενης συλλογής. Μπορεί να μεταγλωττιστεί μόνο αν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση για τη μέθοδο [end()](../../system/smartptr/end/) της υποκείμενης συλλογής. Μπορεί να μεταγλωττιστεί μόνο αν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Λαμβάνει τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει, αλλά ελέγχει ότι ο δείκτης βρίσκεται σε λειτουργία κοινόχρηστης. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Επιστρέφει τον αριθμό των κοινόχρηστων δεικτών που υπάρχουν για το αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Ελέγχει ότι ο τρέχων δείκτης βρίσκεται σε λειτουργία κοινόχρηστης. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί τη [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο στο οποίο δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Επιστρέφει το τρέχον αναφερόμενο αντικείμενο (αν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει (αν υπάρχει) ή nullptr. Το ίδιο με [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Επιστρέφει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει (αν υπάρχει) ή nullptr. Το ίδιο με [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο στο οποίο δείχνει είναι ενός συγκεκριμένου τύπου ή του υποτύπου του. Ακολουθεί τη σημασιολογία του C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε άλλο αντικείμενο από το ιδιοκτησιακό (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε λειτουργία κοινόχρηστης. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε αδύναμη (weak) λειτουργία. |
| [ListPtr](./listptr/)(std::nullptr_t) | Αρχικοποιεί δείκτη null. |
| [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Αρχικοποιεί δείκτη σε καθορισμένη λίστα. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Λαμβάνει αναφορά στο αντικείμενο στο οποίο δείχνει. Ελέγχει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία σύγκρισης λιγότερο (less) για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία σύγκρισης λιγότερο (less) για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Αναθέτει με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται μη χρησιμοποιήσιμο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αντιγράφει-αναθέτει το αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αντιγράφει-αναθέτει το αντικείμενο [SmartPtr](../../system/smartptr/). Εκτελεί τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο δείκτης [List](../list/) είναι null. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Πρόσβαση. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Πρόσβαση. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από τον δείκτη, διασφαλίζει ότι διαχειρίζεται (αν είναι κοινόχρηστος) ή παρακολουθεί (αν είναι αδύναμος) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφοράς του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο στο οποίο δείχνει (αν υπάρχει). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί null-pointer αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο καθορισμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου αν είναι επιτρεπτή. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Επακριβώς, ανταλλάσσει δύο δείκτες, αν και οι δύο είναι στην ίδια λειτουργία. Το x μπορεί να μην είναι χρησιμοποιήσιμο μετά την κλήση. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας έναν νέο πίνακα διαφορετικού τύπου. Χρήσιμο αν σε C# υπάρχει cast πίνακα τύπου που δεν υποστηρίζεται σε C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για την μετάφραση κάποιων κατασκευών κώδικα C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά κρατά έναν ανεξάρτητο και μη διαχειριζόμενο δείκτη p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Αν είναι απαραίτητο, μειώνει τον μετρητή αναφοράς του αντικειμένου στο οποίο δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)