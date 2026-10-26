---
title: DictionaryPtr
second_title: Αναφορά API του Aspose.Slides για C++
description: Κλάση δείκτη λεξικού με υπερφορτωμένους τελεστές. Αυτός ο τύπος είναι δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις είτε ως τιμή είτε ως const αναφορά.
type: docs
weight: 170
url: /el/system.collections.generic/dictionaryptr/
---
## DictionaryPtr κλάση

[Dictionary](../dictionary/) κλάση δείκτη με υπέρφορτες τελεστών. Αυτός ο τύπος είναι ένας δείκτης για διαχείριση της διαγραφής άλλου αντικειμένου. Πρέπει να εκχωρείται στην στοίβα και να περνιέται στις συναρτήσεις είτε ως τιμή είτε ως const αναφορά.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος κλειδιού. |
| V | Τύπος τιμής. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Προσβάσιμος για τη μέθοδο [begin()](../../system/smartptr/begin/) μιας παρακείμενης συλλογής. Συμπιέζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Προσβάσιμος για τη μέθοδο [begin()](../../system/smartptr/begin/) μιας παρακείμενης συλλογής. Συμπιέζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη στον ίδιο του τον τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη σε τύπο βάσης χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast του δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Προσβάσιμος για τη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας παρακείμενης συλλογής. Συμπιέζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Προσβάσιμος για τη μέθοδο [cend()](../../system/smartptr/cend/) μιας παρακείμενης συλλογής. Συμπιέζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο στο οποίο δείχνει. |
|  [DictionaryPtr](./dictionaryptr/)() | Αρχικοποιεί δείκτη null. |
|  [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | Μετατρέπει τον τύπο του δείκτη. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο στο οποίο δείχνει. |
| auto [end](../../system/smartptr/end/)() | Προσβάσιμος για τη μέθοδο [end()](../../system/smartptr/end/) μιας παρακείμενης συλλογής. Συμπιέζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Προσβάσιμος για τη μέθοδο [end()](../../system/smartptr/end/) μιας παρακείμενης συλλογής. Συμπιέζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει ο δείκτης. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Παίρνει τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει ο δείκτης, αλλά ελέγχει ότι ο δείκτης είναι σε κοινή λειτουργία. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Παίρνει τον αριθμό των κοινών δεικτών που υπάρχουν προς το αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Ελέγχει ότι ο τρέχων δείκτης είναι σε κοινή λειτουργία. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο στο οποίο δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Παίρνει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει ο δείκτης (εάν υπάρχει) ή nullptr. Το ίδιο με [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Παίρνει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει ο δείκτης (εάν υπάρχει) ή nullptr. Το ίδιο με [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο στο οποίο δείχνει ο δείκτης είναι συγκεκριμένου τύπου ή του παιδικού του τύπου. Ακολουθεί τη σημασιολογία του C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει εάν ο δείκτης δείχνει σε κάποιο αντικείμενο διαφορετικό από το κατεχόμενο (δημιουργημένο από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει εάν ο δείκτης είναι σε κοινή λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει εάν ο δείκτης είναι σε αδύναμη λειτουργία. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει εάν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει εάν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Παίρνει αναφορά στο αντικείμενο στο οποίο δείχνει ο δείκτης. Ελέγχει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει τη σημασιολογία λιγότερο-σύγκρισης για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει τη σημασιολογία λιγότερο-σύγκρισης για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Μεταθέτει την ανάθεση του αντικειμένου [SmartPtr](../../system/smartptr/). x γίνεται άχρηστο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αντιγράφει την ανάθεση του αντικειμένου [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αντιγράφει την ανάθεση του αντικειμένου [SmartPtr](../../system/smartptr/). Εκτελεί τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Θέτει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει εάν ο δείκτης δείχνει σε nullptr. |
| V\& [operator[]](./operator[]/)(const X\&) const | Τελεστικό πρόσβασης για εργασία με μετατροπή τύπου κλειδιού. |
| V\& [operator[]](./operator[]/)(const T\&) const | Τελεστικό πρόσβασης. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από τον δείκτη, διασφαλίζοντας ότι διαχειρίζεται (εάν είναι κοινός) ή παρακολουθεί (εάν είναι αδύναμος) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο στο οποίο δείχνει ο δείκτης. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφορών του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο στο οποίο δείχνει ο δείκτης (εάν υπάρχει). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) με null-pointer της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο συγκεκριμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου εάν επιτρέπεται. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Στην ουσία, ανταλλάσσει δύο δείκτες, εφόσον είναι και οι δύο της ίδιας λειτουργίας. x μπορεί να είναι άχρηστο μετά την κλήση. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο εάν σε C# υπάρχει cast πίνακα που δεν υποστηρίζεται σε C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί άδειο πίνακα. Χρησιμοποιείται για τη μετάφραση ορισμένων κατασκευών κώδικα C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά κρατά έναν άσχετο και αδιαχειρίσιμο δείκτη p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Κάνει cast του δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο στο οποίο δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν χρειάζεται, μειώνει τον μετρητή αναφορών του αντικειμένου στο οποίο δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)