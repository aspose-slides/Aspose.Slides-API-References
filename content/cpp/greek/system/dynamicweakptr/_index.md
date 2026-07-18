---
title: DynamicWeakPtr
second_title: Αναφορά API του Aspose.Slides για C++
description: Κλάση έξυπνου δείκτη που παρακολουθεί τις λειτουργίες των δεικτών των παραμέτρων προτύπου του αποθηκευμένου αντικειμένου και τις ενημερώνει μετά από κάθε ανάθεση. Αυτός ο τύπος είναι δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Πρέπει να εκχωρείται στη στοίβα και να περνάει σε συναρτήσεις είτε ως τιμή είτε ως σταθερή αναφορά.
type: docs
weight: 781
url: /el/system/dynamicweakptr/
---
## DynamicWeakPtr κλάση

Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Pointee | τύπος. |
| trunkMode | Λειτουργία του ίδιου του έξυπνου δείκτη, shared ή weak. |
| weakLeafs | Δείκτες των παραμέτρων προτύπου του αποθηκευμένου τύπου που πρέπει να οριστούν σε λειτουργία weak pointer. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Πρόσβαση στην μέθοδο [begin()](../smartptr/begin/) μιας υποκείμενης συλλογής. Συντάσσεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Πρόσβαση στη μέθοδο [begin()](../smartptr/begin/) μιας υποκείμενης συλλογής. Συντάσσεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Μετατρέπει τον δείκτη στον ίδιο του τύπο. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Μετατρέπει τον δείκτη σε βασικό τύπο χρησιμοποιώντας static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Μετατρέπει τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Μετατρέπει τον δείκτη σε παράγωγο τύπο χρησιμοποιώντας dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Πρόσβαση στη μέθοδο [cbegin()](../smartptr/cbegin/) μιας υποκείμενης συλλογής. Συντάσσεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Πρόσβαση στη μέθοδο [cend()](../smartptr/cend/) μιας υποκείμενης συλλογής. Συντάσσεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας const_cast στο αντικείμενο που δείχνει. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας dynamic_cast στο αντικείμενο που δείχνει. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Δημιουργεί μηδενικό έξυπνο δείκτη. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Δημιουργεί έξυπνο δείκτη που δείχνει σε δεδομένο αντικείμενο. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Δημιουργεί αντίγραφο ενός έξυπνου δείκτη. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Δημιουργεί αντίγραφο ενός έξυπνου δείκτη. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Δημιουργεί αντίγραφο ενός έξυπνου δείκτη. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Δημιουργεί μεταφορά ενός έξυπνου δείκτη. |
| auto [end](../smartptr/end/)() | Πρόσβαση στη μέθοδο [end()](../smartptr/end/) μιας υποκείμενης συλλογής. Συντάσσεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Πρόσβαση στη μέθοδο [end()](../smartptr/end/) μιας υποκείμενης συλλογής. Συντάσσεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Παίρνει τη λειτουργία του δείκτη. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει, αλλά εξασφαλίζει ότι ο δείκτης βρίσκεται σε λειτουργία shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Παίρνει τον αριθμό των shared δεικτών που υπάρχουν για το αναφερόμενο αντικείμενο, συμπεριλαμβανομένου του τρέχοντος. Εξασφαλίζει ότι ο τρέχων δείκτης βρίσκεται σε λειτουργία shared. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Καλεί τη μέθοδο [GetHashCode()](../smartptr/gethashcode/) στο αντικείμενο στο οποίο δείχνει. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Παίρνει το τρέχον αναφερόμενο αντικείμενο (αν υπάρχει) ή ρίχνει εξαίρεση. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει (αν υπάρχει) ή nullptr. Το ίδιο με [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Παίρνει το αναφερόμενο αντικείμενο. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Παίρνει το αντικείμενο στο οποίο δείχνει (αν υπάρχει) ή nullptr. Το ίδιο με [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο στο οποίο δείχνει είναι συγκεκριμένου τύπου ή τύπο παιδιού του. Ακολουθεί τη σημασιολογία 'is' της C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Ελέγχει εάν ο δείκτης δείχνει σε αντικείμενο διαφορετικό από το ιδιοκτησιακό (δημιουργήθηκε από κατασκευαστή aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Ελέγχει εάν ο δείκτης βρίσκεται σε λειτουργία shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Ελέγχει εάν ο δείκτης βρίσκεται σε λειτουργία weak. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Ελέγχει εάν ο δείκτης δεν είναι μηδενικός. |
| **bool** [operator!](../smartptr/operator_not/)() const | Ελέγχει εάν ο δείκτης είναι μηδενικός. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Παίρνει αναφορά στο αντικείμενο στο οποίο δείχνει. Εξασφαλίζει ότι ο δείκτης δεν είναι μηδενικός. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αναφερόμενου αντικειμένου. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Παρέχει τη σημασιολογία σύγκρισης λιγότερο για την κλάση [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Παρέχει τη σημασιολογία σύγκρισης λιγότερο για την κλάση [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Αναθέτει με μεταφορά τον έξυπνο δείκτη. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Αναθέτει με αντιγραφή τον έξυπνο δείκτη. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Αναθέτει με αντιγραφή τον έξυπνο δείκτη. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Αναθέτει έξυπνο δείκτη. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Ορίζει τον έξυπνο δείκτη σε μηδενικό. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ελέγχει εάν ο έξυπνος δείκτης είναι μηδενικός. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Αφαιρεί το aliasing (δημιουργημένο από κατασκευαστή aliasing) από τον δείκτη, διασφαλίζει ότι διαχειρίζεται (αν είναι shared) ή παρακολουθεί (αν είναι weak) το ίδιο αντικείμενο στο οποίο δείχνει. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Ορίζει το αντικείμενο στο οποίο δείχνει. |
| void [reset](../smartptr/reset/)() | Κάνει τον δείκτη να δείχνει σε nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τους μετρητές αναφορών του αναφερόμενου αντικειμένου. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Καλεί τη μέθοδο SetTemplateWeakPtr() στο αντικείμενο στο οποίο δείχνει (αν υπάρχει). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../smartptr/) της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί αντικείμενο [SmartPtr](../smartptr/) μηδενικού δείκτη της απαιτούμενης λειτουργίας. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί [SmartPtr](../smartptr/) που δείχνει στο συγκεκριμένο αντικείμενο, ή μετατρέπει ακατέργαστο δείκτη σε [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί αντιγραφή του αντικειμένου [SmartPtr](../smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί αντιγραφή του αντικειμένου [SmartPtr](../smartptr/). Και οι δύο δείκτες δείχνουν στο ίδιο αντικείμενο μετά. Εκτελεί μετατροπή τύπου αν επιτρέπεται. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί με μεταφορά το αντικείμενο [SmartPtr](../smartptr/). Στην ουσία, ανταλλάσσει δύο δείκτες, αν και οι δύο είναι της ίδιας λειτουργίας. Το x μπορεί να γίνει μη χρησιμοποιήσιμο μετά την κλήση. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Μετατρέπει τον τύπο του αναφερόμενου πίνακα δημιουργώντας έναν νέο πίνακα διαφορετικού τύπου. Χρήσιμο εάν στην C# υπάρχει μετατροπή τύπου πίνακα που δεν υποστηρίζεται στην C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Αρχικοποιεί κενό πίνακα. Χρησιμοποιείται για τη μετάφραση κάποιων κατασκευών κώδικα C#. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Δημιουργεί ένα [SmartPtr](../smartptr/) που μοιράζεται πληροφορίες ιδιοκτησίας με την αρχική τιμή του ptr, αλλά διατηρεί έναν ανεξάρτητο και ασύγχρονο δείκτη p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Μετατρέπει τον δείκτη σε διαφορετικό τύπο χρησιμοποιώντας static_cast στο αντικείμενο στο οποίο δείχνει. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Μετατρέπει οποιονδήποτε τύπο δείκτη σε δείκτη προς [Object](../object/). Δεν απαιτεί ο τύπος Pointee_ να είναι πλήρης. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Συντόμευση για την λήψη του αντικειμένου [System::TypeInfo](../typeinfo/) για τον τύπο Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Καταστρέφει το αντικείμενο [SmartPtr](../smartptr/). Εάν απαιτείται, μειώνει τον μετρητή αναφορών του αντικειμένου στο οποίο δείχνει και διαγράφει το αντικείμενο. |

## Τύποι ορισμού

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) ψευδώνυμο βασικής κλάσης. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Ψευδώνυμο τύπου εαυτού. |
| [Pointee_](./pointee_/) | Τύπος δείκτη. |

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)