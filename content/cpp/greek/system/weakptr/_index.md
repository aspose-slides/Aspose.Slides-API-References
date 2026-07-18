---
title: WeakPtr
second_title: Aspose.Slides για C++ Αναφορά API
description: "Υποκατηγορία του System::SmartPtr που θέτει τον εαυτό της σε αδύναμη λειτουργία κατά την κατασκευή. Παρακαλούμε σημειώστε ότι αυτή η κλάση δεν εγγυάται ότι το αντίγραφό της θα παραμείνει πάντα σε αδύναμη λειτουργία, καθώς η set_Mode() παραμένει προσβάσιμη. Αυτός ο τύπος είναι ένας δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να δεσμεύεται στη στοίβα και να μεταβιβάζεται σε συναρτήσεις είτε με τιμή είτε με const αναφορά."
type: docs
weight: 1470
url: /el/system/weakptr/
---
## WeakPtr κλάση

Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος pointee. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Πρόσβαση στη μέθοδο [begin()](../smartptr/begin/) μιας υποκείμενης συλλογής. Συγκομπιλάρει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../smartptr/begin/) μιας υποκείμενης συλλογής. Συγκομπιλάρει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Κάνει cast τον δείκτη στον δικό του τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Κάνει cast τον δείκτη στον βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Κάνει cast τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Κάνει cast τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../smartptr/cbegin/) μιας υποκείμενης συλλογής. Συγκομπιλάρει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../smartptr/cend/) μιας υποκείμενης συλλογής. Συγκομπιλάρει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
| auto [end](../smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../smartptr/end/) μιας υποκείμενης συλλογής. Συγκομπιλάρει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../smartptr/end/) μιας υποκείμενης συλλογής. Συγκομπιλάρει μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Ελέγχει αν το αναφερόμενο αντικείμενο έχει ήδη διαγραφεί. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Επιστρέφει το αντικείμενο προς το οποίο δείχνει. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Αποκτά τη λειτουργία του δείκτη. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Επιστρέφει το αντικείμενο προς το οποίο δείχνει, αλλά ελέγχει ότι ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Επιστρέφει τον αριθμό των κοινών δεικτών που υπάρχουν προς το αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Ελέγχει ότι ο τρέχων δείκτης είναι σε κοινή λειτουργία. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Επιστρέφει το αναφερόμενο αντικείμενο. Ελέγχει ότι ο δείκτης είναι σε αδύναμη λειτουργία. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Καλεί τη [GetHashCode()](../smartptr/gethashcode/) στο αντικείμενο προς το οποίο δείχνει. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Επιστρέφει το τρέχον αναφερόμενο αντικείμενο (εάν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Επιστρέφει το αντικείμενο προς το οποίο δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Επιστρέφει το αναφερόμενο αντικείμενο. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Επιστρέφει το αντικείμενο προς το οποίο δείχνει (εάν υπάρχει) ή nullptr. Το ίδιο με [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο προς το οποίο δείχνει είναι συγκεκριμένου τύπου ή τύπου παιδιού του. Ακολουθεί τη σημασία του 'is' στη C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Ελέγχει αν ο δείκτης δείχνει σε αντικείμενο διαφορετικό από το ιδιοκτησιακό (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε κοινή λειτουργία. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Ελέγχει αν ο δείκτης βρίσκεται σε αδύναμη λειτουργία. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Ελέγχει αν ο δείκτης δεν είναι null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Ελέγχει αν ο δείκτης είναι null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Επιστρέφει αναφορά στο αντικείμενο προς το οποίο δείχνει. Ελέγχει ότι ο δείκτης δεν είναι null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Παρέχει τη σημασία της σύγκρισης less για την κλάση [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Παρέχει τη σημασία της σύγκρισης less για την κλάση [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Αντιστοιχίζει τιμή στον αδύναμο δείκτη. Καλεί τον συγκεκριμένο τελεστή ανάθεσης του SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Κάνει move-assign το αντικείμενο [SmartPtr](../smartptr/). Το x γίνεται άχρηστο. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Κάνει copy-assign το αντικείμενο [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Κάνει copy-assign το αντικείμενο [SmartPtr](../smartptr/). Κάνει τις απαιτούμενες μετατροπές τύπων. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Αντιστοιχίζει ακατέργαστο δείκτη στο αντικείμενο [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Ορίζει την τιμή του δείκτη σε nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν ο αδύναμος δείκτης είναι null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από τον δείκτη, διασφαλίζει ότι διαχειρίζεται (αν είναι shared) ή παρακολουθεί (αν είναι weak) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Ορίζει το αντικείμενο προς το οποίο δείχνει. |
| void [reset](../smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφορών του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο προς το οποίο δείχνει (εάν υπάρχει). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../smartptr/) της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../smartptr/) null-pointer της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί [SmartPtr](../smartptr/) που δείχνει στο συγκεκριμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί με αντιγραφή το αντικείμενο [SmartPtr](../smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Κάνει μετατροπή τύπου αν επιτρέπεται. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί με μετακίνηση το αντικείμενο [SmartPtr](../smartptr/). Στην πράξη, ανταλλάσσει δύο δείκτες, αν είναι και οι δύο στην ίδια λειτουργία. Το x μπορεί να γίνει άχρηστο μετά την κλήση. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας έναν νέο πίνακα διαφορετικού τύπου. Χρήσιμο αν στη C# υπάρχει μετατροπή τύπου πίνακα που δεν υποστηρίζεται στην C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για μετάφραση ορισμένων κατασκευών κώδικα C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά διακρατά έναν άσχετο και ανεξάρτητο δείκτη p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Κάνει cast τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Σύντομη πρόσβαση για λήψη του αντικειμένου [System::TypeInfo](../typeinfo/) για τον τύπο Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Δημιουργεί null pointer. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Δημιουργεί αδύναμο δείκτη προς το συγκεκριμένο αντικείμενο. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Δημιουργεί αδύναμο δείκτη που αναφέρεται στον ίδιο δείκτη που δείχνει το ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Δημιουργεί αδύναμο δείκτη που αναφέρεται στον ίδιο δείκτη που δείχνει το x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Δημιουργεί με αντιγραφή αδύναμο δείκτη. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Δημιουργεί με αντιγραφή αδύναμο δείκτη. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Δημιουργεί με μετακίνηση αδύναμο δείκτη. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../smartptr/). Αν απαιτείται, μειώνει τον μετρητή αναφορών του αντικειμένου που δείχνει και διαγράφει το αντικείμενο. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Ψευδώνυμο για την αντίστοιχη κλάση [SmartPtr](../smartptr/). |
| [WeakPtr_](./weakptr_/) | Ψευδώνυμο για τον τύπο του εαυτού. |
| [Pointee_](./pointee_/) | Τύπος που δείχνει. |

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)