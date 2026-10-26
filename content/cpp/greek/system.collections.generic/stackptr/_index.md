---
title: StackPtr
second_title: Aspose.Slides για C++ API Αναφορά
description: Δείκτης στο stack. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλου αντικειμένου. Θα πρέπει να εκχωρείται στο stack και να περνιέται σε συναρτήσεις είτε με τιμή είτε με const αναφορά.
type: docs
weight: 612
url: /el/system.collections.generic/stackptr/
---
## StackPtr κλάση

[Stack](../stack/) δείκτης. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλου αντικειμένου. Θα πρέπει να εκχωρείται στο stack και να περνιέται σε συναρτήσεις είτε με τιμή είτε με const αναφορά.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Element type. |

## Μέθοδοι

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Συγκεντώνεται μόνο αν το SmartPtr_ είναι ειδικευμένος τύπος με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Συγκεντώνεται μόνο αν το SmartPtr_ είναι ειδικευμένος τύπος με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει το δείκτη στον ίδιο του τον τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει το δείκτη στον βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει το δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει το δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας υποκείμενης συλλογής. Συγκεντώνεται μόνο αν το SmartPtr_ είναι ειδικευμένος τύπος με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../../system/smartptr/cend/) μιας υποκείμενης συλλογής. Συγκεντώνεται μόνο αν το SmartPtr_ είναι ειδικευμένος τύπος με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Μετατρέπει το δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο στο οποίο δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Μετατρέπει το δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο στο οποίο δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Συγκεντώνεται μόνο αν το SmartPtr_ είναι ειδικευμένος τύπος με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Συγκεντώνεται μόνο αν το SmartPtr_ είναι ειδικευμένος τύπος με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Λαμβάνει τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει, αλλά ελέγχει ότι ο δείκτης είναι σε κοινή λειτουργία. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Λαμβάνει τον αριθμό των κοινών δεικτών που υπάρχουν για το αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Εξασφαλίζει ότι ο τρέχων δείκτης βρίσκεται σε κοινή λειτουργία. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί τη μέθοδο [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο στο οποίο δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Λαμβάνει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή πετάει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει (εάν υπάρχει) ή nullptr. Ίδιο με [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Λαμβάνει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει (εάν υπάρχει) ή nullptr. Ίδιο με [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο στο οποίο δείχνει είναι συγκεκριμένου τύπου ή του παιδικού του τύπου. Ακολουθεί τη σημασιολογία του C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε διαφορετικό αντικείμενο από αυτό που κατέχει (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε αδύναμη λειτουργία. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Λαμβάνει αναφορά στο αντικείμενο στο οποίο δείχνει. Εξασφαλίζει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία λιγότερο-συγκρίσιμη για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία λιγότερο-συγκρίσιμη για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Αναθέτει με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται αχρησιμοποίητο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αναθέτει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αναθέτει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Κάνει τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο δείκτης δείχνει σε nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από το δείκτη, διασφαλίζοντας ότι διαχειρίζεται (αν είναι shared) ή παρακολουθεί (αν είναι weak) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει το δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφοράς του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο στο οποίο δείχνει (εφόσον υπάρχει). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί το αντικείμενο [SmartPtr](../../system/smartptr/) με την απαιτούμενη λειτουργία. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) με null-pointer στην απαιτούμενη λειτουργία. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο καθορισμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου αν επιτρέπεται. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Σχεδόν, ανταλλάσσει δύο δείκτες, αν είναι και οι δύο στην ίδια λειτουργία. Το x μπορεί να γίνει αχρησιμοποίητο μετά την κλήση. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο αν σε C# υπάρχει μετατροπή τύπου πίνακα που δεν υποστηρίζεται σε C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για τη μετάφραση ορισμένων κατασκευών κώδικα C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά κρατά έναν άσχετο και αμηχανή δείκτη p. |
|  [StackPtr](./stackptr/)() | Δημιουργεί null pointer. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Δημιουργεί δείκτη που αναφέρεται σε συγκεκριμένο stack. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Μετατρέπει το δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο στο οποίο δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί να είναι πλήρης ο τύπος Pointee_. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Σύντομη κλήση για λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφοράς του αντικειμένου στο οποίο δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Ονομαχώρος [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)