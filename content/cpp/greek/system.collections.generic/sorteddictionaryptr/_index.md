---
title: SortedDictionaryPtr
second_title: Aspose.Slides για C++ Αναφορά API
description: Δείκτης σε ταξινομημένο λεξικό με τελεστές πρόσβασης. Αυτός ο τύπος είναι δείκτης για τη διαχείριση της διαγραφής άλλου αντικειμένου. Θα πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις είτε με τιμή είτε με σταθερή αναφορά.
type: docs
weight: 534
url: /el/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr κλάση


Sorted dictionary pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<SortedDictionary<T, V>>
```

## Μεθόδοι

| Method | Περιγραφή |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Συγκεντρώνεται μόνο εάν το SmartPtr_ είναι εξειδικευμένος τύπος με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Συγκεντρώνεται μόνο εάν το SmartPtr_ είναι εξειδικευμένος τύπος με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη στον ίδιο του τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη στον βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη στον παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη στον παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας υποκείμενης συλλογής. Συγκεντρώνεται μόνο εάν το SmartPtr_ είναι εξειδικευμένος τύπος με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../../system/smartptr/cend/) μιας υποκείμενης συλλογής. Συγκεντρώνεται μόνο εάν το SmartPtr_ είναι εξειδικευμένος τύπος με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Συγκεντρώνεται μόνο εάν το SmartPtr_ είναι εξειδικευμένος τύπος με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Συγκεντρώνεται μόνο εάν το SmartPtr_ είναι εξειδικευμένος τύπος με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Λαμβάνει τη λειτουργία δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει, αλλά επιβεβαιώνει ότι ο δείκτης είναι σε κοινή κατάσταση. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Λαμβάνει τον αριθμό των κοινών δεικτών που υπάρχουν για το αναφερθέν αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Επιβεβαιώνει ότι ο τρέχων δείκτης βρίσκεται σε κοινή κατάσταση. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί τη [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο που δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Λαμβάνει το τρέχον αναφερθέν αντικείμενο (εάν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Λαμβάνει το αναφερθέν αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο στο οποίο δείχνει είναι συγκεκριμένου τύπου ή τύπου-παιδιού του. Ακολουθεί τη σημασιολογία του C# ‘is’. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε αντικείμενο διαφορετικό από το κατέχόμενο (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει αν ο δείκτης είναι σε κοινή λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει αν ο δείκτης είναι σε αδυνατή λειτουργία. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Λαμβάνει αναφορά στο αντικείμενο στο οποίο δείχνει. Επιβεβαιώνει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερθέντος αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία σύγκρισης μικρότερου για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία σύγκρισης μικρότερου για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Κάνει μετακίνηση (move-assign) στο αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται μη χρησιμοποιήσιμο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αντιγράφει-αναθέτει στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αντιγράφει-αναθέτει στο αντικείμενο [SmartPtr](../../system/smartptr/). Κάνει τις απαιτούμενες μετατροπές τύπων. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο δείκτης δείχνει σε nullptr. |
| V\& [operator[]](./operator[]/)(const T\&) const | Συνάρτηση πρόσβασης. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (που δημιουργείται από κατασκευαστή aliasing) από τον δείκτη, εξασφαλίζοντας ότι διαχειρίζεται (αν είναι κοινό) ή παρακολουθεί (αν είναι αδυνατό) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφοράς του αναφερθέντος αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο που δείχνει (εάν υπάρχει). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί το αντικείμενο [SmartPtr](../../system/smartptr/) απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) null-pointer απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο καθορισμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί μέσω αντιγραφής το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί μέσω αντιγραφής το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου αν επιτρέπεται. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί μέσω μετακίνησης το αντικείμενο [SmartPtr](../../system/smartptr/). Στην ουσία ανταλλάσσει δύο δείκτες, εάν και οι δύο είναι στην ίδια λειτουργία. Το x μπορεί να είναι μη χρησιμοποιήσιμο μετά την κλήση. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερθέντος πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο εάν σε C# υπάρχει cast τύπου πίνακα που δεν υποστηρίζεται στην C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί άδειο πίνακα. Χρησιμοποιείται για τη μετάφραση κάποιων δομών κώδικα C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά περιέχει έναν ανεξάρτητο και αδιαχειρίσιμο δείκτη p. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)() | Δημιουργεί δείκτη null. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedDictionary](../sorteddictionary/)\<T, V\>\>\&) | Δημιουργεί δείκτη προς το καθορισμένο ταξινομημένο λεξικό. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφοράς του αντικείμενο που δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)