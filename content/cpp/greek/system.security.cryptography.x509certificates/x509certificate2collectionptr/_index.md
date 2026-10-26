---
title: X509Certificate2CollectionPtr
second_title: Aspose.Slides για C++ Αναφορά API
description: Δείκτης σε συλλογή X509 πιστοποιητικών. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις είτε με τιμή είτε με σταθερή αναφορά.
type: docs
weight: 66
url: /el/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr κλάση

Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι ειδικός τύπος με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι ειδικός τύπος με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη στον ίδιο του τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη σε τύπο βάσης χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη σε τύπο παράγωγο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Κάνει cast τον δείκτη σε τύπο παράγωγο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι ειδικός τύπος με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../../system/smartptr/cend/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι ειδικός τύπος με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο στο οποίο δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο στο οποίο δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι ειδικός τύπος με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι ειδικός τύπος με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Επιστρέφει το αντικείμενο που δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Επιστρέφει τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Επιστρέφει το αντικείμενο που δείχνει, αλλά ελέγχει ότι ο δείκτης είναι σε κοινή λειτουργία. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Επιστρέφει τον αριθμό των κοινών δεικτών που υπάρχουν στο αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Ελέγχει ότι ο τρέχων δείκτης είναι σε κοινή λειτουργία. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί το [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο που δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Επιστρέφει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή πετάει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Επιστρέφει το αντικείμενο που δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με το [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Επιστρέφει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Επιστρέφει το αντικείμενο που δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με το [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο που δείχνει είναι συγκεκριμένου τύπου ή υποτύπου. Ακολουθεί τη σημασιολογία «is» της C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε άλλο αντικείμενο από το ιδιοκτητούμενο (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει αν ο δείκτης είναι σε κοινή λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει αν ο δείκτης είναι σε αδυναμική λειτουργία. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Επιστρέφει αναφορά στο αντικείμενο που δείχνει. Ελέγχει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία λιγότερο-σύγκρισης για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία λιγότερο-σύγκρισης για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Αναθέτει με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται μη-χρησιμοποιήσιμο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αναθέτει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αναθέτει με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Κάνει τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο δείκτης δείχνει σε nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | Πρόσβαση. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργήθηκε από κατασκευαστή aliasing) από τον δείκτη, διασφαλίζοντας ότι διαχειρίζεται (αν είναι κοινός) ή παρακολουθεί (αν είναι αδυναμικός) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο που δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει μετρητές αναφορών του αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο που δείχνει (εάν υπάρχει). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) null-pointer της απαιτούμενης λειτουργίας. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο καθορισμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου αν επιτρέπεται. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Σε ουσία, ανταλλάσσει δύο δείκτες, αν και οι δύο είναι της ίδιας λειτουργίας. Το x μπορεί να γίνει μη-χρησιμοποιήσιμο μετά την κλήση. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο όταν στην C# υπάρχει cast πίνακα που δεν υποστηρίζεται στην C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για μετάφραση κάποιων κώδικα C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά κρατά ανεξάρτητο και μη διαχειριζόμενο δείκτη p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο στο οποίο δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για τη λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
| [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | Κατασκευαστής null pointer. |
| [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | Κατασκευαστής. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφορών του αντικειμένου στο οποίο δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)