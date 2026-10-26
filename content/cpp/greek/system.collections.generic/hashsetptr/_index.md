---
title: HashSetPtr
second_title: Aspose.Slides για την Αναφορά API C++
description: Δείκτης για τη διατήρηση των αναφορών HashSet. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Πρέπει να εκχωρείται στο stack και να περνιέται σε συναρτήσεις είτε ως τιμή είτε ως const αναφορά.
type: docs
weight: 235
url: /el/system.collections.generic/hashsetptr/
---
## HashSetPtr κλάση

Δείκτης για τη διατήρηση των [HashSet](../hashset/) αναφορών. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Πρέπει να εκχωρείται στο stack και να περνιέται σε συναρτήσεις είτε ως τιμή είτε ως const αναφορά.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Μεθόδοι

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας εσωτερικής συλλογής. Συγκομπιλίζει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας εσωτερικής συλλογής. Συγκομπιλίζει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη στον ίδιο του τον τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη σε βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας εσωτερικής συλλογής. Συγκομπιλίζει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../../system/smartptr/cend/) μιας εσωτερικής συλλογής. Συγκομπιλίζει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας εσωτερικής συλλογής. Συγκομπιλίζει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας εσωτερικής συλλογής. Συγκομπιλίζει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Επιστρέφει το αντικείμενο που δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Αποκτά τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Επιστρέφει το αντικείμενο που δείχνει, αλλά ελέγχει ότι ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Επιστρέφει τον αριθμό των κοινών δεικτών που υπάρχουν για το αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Ελέγχει ότι ο τρέχων δείκτης είναι σε κοινή λειτουργία. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί τη μέθοδο [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο που δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Επιστρέφει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Επιστρέφει το αντικείμενο που δείχνει (εάν υπάρχει) ή nullptr. Ίδιο με [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Επιστρέφει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Επιστρέφει το αντικείμενο που δείχνει (εάν υπάρχει) ή nullptr. Ίδιο με [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | Κατασκευαστής μηδενικού δείκτη. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | Κατασκευαστής αντιγραφής. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο που δείχνει είναι συγκεκριμένου τύπου ή του υποτύπου του. Ακολουθεί τη σημασιολογία του C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε αντικείμενο διαφορετικό από το ιδιοκτησιακό (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε ασθενή λειτουργία. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Επιστρέφει αναφορά στο αντικείμενο που δείχνει. Ελέγχει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία συγκριτικής μικρότερης τιμής για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία συγκριτικής μικρότερης τιμής για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Αντιστοιχίζει με κίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται αχρησιμοποίητο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αντιστοιχίζει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αντιστοιχίζει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Εκτελεί τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αντιστοιχίζει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο δείκτης δείχνει σε nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από το δείκτη, εξασφαλίζοντας ότι διαχειρίζεται (εάν είναι κοινό) ή παρακολουθεί (εάν είναι ασθενές) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο που δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να τροποποιήσει τους μετρητές αναφορών του αντικειμένου που αναφέρεται. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο που δείχνει (εάν υπάρχει). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) μηδενικού δείκτη της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο καθορισμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Κατασκευάζει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Κατασκευάζει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου εάν επιτρέπεται. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Κατασκευάζει με κίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Στην πράξη, ανταλλάσσει δύο δείκτες, αν και οι δύο είναι στην ίδια λειτουργία. Το x μπορεί να γίνει αχρησιμοποίητο μετά την κλήση. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας έναν νέο πίνακα διαφορετικού τύπου. Χρήσιμο όταν στο C# υπάρχει cast τύπου πίνακα που δεν υποστηρίζεται στην C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για τη μετάφραση ορισμένων κατασκευών κώδικα C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά διατηρεί έναν άσχετο και μη διαχειριζόμενο δείκτη p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφορών του αντικειμένου που δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)