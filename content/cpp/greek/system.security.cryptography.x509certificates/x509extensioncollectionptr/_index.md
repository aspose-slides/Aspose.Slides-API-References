---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides για C++ Αναφορά API
description: Δείκτης σε συλλογή επεκτάσεων X509. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλου αντικειμένου. Θα πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις είτε ως τιμή είτε ως σταθερή αναφορά.
type: docs
weight: 170
url: /el/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr κλάση

Δείκτης σε συλλογή επεκτάσεων X509. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλου αντικειμένου. Πρέπει να εκχωρείται στην στοίβα και να περνιέται σε συναρτήσεις είτε από τιμή είτε από σταθερή αναφορά.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../../system/smartptr/begin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη στον ίδιο του τον τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη σε βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Μετατρέπει τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../../system/smartptr/cbegin/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../../system/smartptr/cend/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
| auto [end](../../system/smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../../system/smartptr/end/) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Επιστρέφει τη λειτουργία του δείκτη. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει, αλλά ελέγχει ότι ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Επιστρέφει τον αριθμό των κοινών δεικτών που υπάρχουν στο αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Εξασφαλίζει ότι ο τρέχων δείκτης βρίσκεται σε κοινή λειτουργία. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Καλεί τη μέθοδο [GetHashCode()](../../system/smartptr/gethashcode/) στο αντικείμενο που δείχνει. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Επιστρέφει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει (εφόσον υπάρχει) ή nullptr. Ίδιο με [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Επιστρέφει το αναφερόμενο αντικείμενο. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Επιστρέφει το αντικείμενο στο οποίο δείχνει (εφόσον υπάρχει) ή nullptr. Ίδιο με [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο στο οποίο δείχνει είναι συγκεκριμένου τύπου ή τύπου απογόνου. Ακολουθεί τη σημασιολογία του C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε αντικείμενο διαφορετικό από το ίδιο που κατέχει (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε αδύναμη λειτουργία. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Επιστρέφει αναφορά στο αντικείμενο στο οποίο δείχνει. Εξασφαλίζει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Παρέχει σημασιολογία σύγκρισης μικρότερου για την κλάση [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Παρέχει σημασιολογία σύγκρισης μικρότερου για την κλάση [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Αντιστοιχεί με μετακίνηση το αντικείμενο [SmartPtr](../../system/smartptr/). Το x γίνεται αχρησιμοποίητο. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Αντιστοιχεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Αντιστοιχεί με αντιγραφή το αντικείμενο [SmartPtr](../../system/smartptr/). Εκτελεί τις απαιτούμενες μετατροπές τύπου. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Αναθέτει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο δείκτης δείχνει σε nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | Πρόσβαση. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από τον δείκτη, εξασφαλίζει ότι διαχειρίζεται (αν είναι κοινό) ή παρακολουθεί (αν είναι αδύναμο) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ορίζει το αντικείμενο στο οποίο δείχνει. |
| void [reset](../../system/smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφοράς του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο στο οποίο δείχνει (εάν υπάρχει). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) τύπου null-pointer της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί [SmartPtr](../../system/smartptr/) που δείχνει στο καθορισμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντίγραφο του αντικειμένου [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντίγραφο του αντικειμένου [SmartPtr](../../system/smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου εάν επιτρέπεται. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../../system/smartptr/) με μετακίνηση. Στην ουσία, ανταλλάσσει δύο δείκτες, εφόσον έχουν την ίδια λειτουργία. Το x μπορεί να είναι αχρησιμοποίητο μετά την κλήση. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας νέο πίνακα διαφορετικού τύπου. Χρήσιμο όταν σε C# υπάρχει μετατροπή τύπου πίνακα που δεν υποστηρίζεται σε C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για τη μετάφραση ορισμένων δομών κώδικα C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../../system/smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά κρατά έναν ανεξάρτητο και μη διαχειριζόμενο δείκτη p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../../system/object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Συντόμευση για λήψη του αντικειμένου [System::TypeInfo](../../system/typeinfo/) για τον τύπο Pointee_. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | Κατασκευαστής null pointer. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | Κατασκευαστής. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../../system/smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφοράς του αντικειμένου στο οποίο δείχνει και διαγράφει το αντικείμενο. |

## Δείτε επίσης

* Κλάση [SmartPtr](../../system/smartptr/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)