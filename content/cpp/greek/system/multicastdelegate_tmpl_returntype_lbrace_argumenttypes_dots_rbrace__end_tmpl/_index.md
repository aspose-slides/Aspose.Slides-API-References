---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει μια συλλογή αντιπροσώπων. Αυτός ο τύπος πρέπει να κατανεμηθεί στη στοίβα και να περάσει σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 1080
url: /el/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> κλάση

Αντιπροσωπεύει μια συλλογή αντιπροσώπων. Αυτό το είδος θα πρέπει να κατανεμηθεί στη στοίβα και να περάσει σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για να διαχειριστείτε αντικείμενα αυτού του τύπου.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ReturnType | Τύπος επιστροφής των προσβάσιμων οντοτήτων που δείχνουν οι εκάστοτε αντιπρόσωποι στη συλλογή |
| ArgumentTypes | Κατάλογος ορισμάτων των προσβάσιμων οντοτήτων που δείχνουν οι εκάστοτε αντιπρόσωποι στη συλλογή |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Προσθέτει τον συγκεκριμένο αντιπρόσωπο στη συλλογή. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Προσθέτει το συγκεκριμένο αντικείμενο συνάρτησης στη συλλογή αντιπροσώπων. Το αντικείμενο συνάρτησης μετατρέπεται σε τύπο αντιπρόσωπου Callback πριν προστεθεί στη συλλογή. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Προσθέτει το συγκεκριμένο αντικείμενο MulticastDelegate στη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Προσθέτει τη συγκεκριμένη μη-στατική μέθοδο του συγκεκριμένου αντικειμένου στη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Προσθέτει τη συγκεκριμένη μη-στατική μέθοδο του συγκεκριμένου αντικειμένου στη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Αφαιρεί τον συγκεκριμένο αντιπρόσωπο από τη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Αφαιρεί τη συγκεκριμένη μη-στατική μέθοδο του συγκεκριμένου αντικειμένου από τη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Αφαιρεί τη συγκεκριμένη μη-στατική μέθοδο του συγκεκριμένου αντικειμένου από τη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Αφαιρεί το συγκεκριμένο αντικείμενο MulticastDelegate από τη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Αφαιρεί όλους τους αντιπροσώπους από τη συλλογή αντιπροσώπων. |
| **bool** [empty](./empty/)() const | Καθορίζει αν η συλλογή αντιπροσώπων είναι κενή. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Καλεί όλους τους αντιπροσώπους που είναι αυτή τη στιγμή στη συλλογή αντιπροσώπων. Οι αντιπρόσωποι καλούνται με την ίδια σειρά με την οποία προστέθηκαν στη συλλογή. Η μέθοδος μπλοκάρει ενώ οι αντιπρόσωποι εκτελούνται. |
| **bool** [IsNull](./isnull/)() const | Καθορίζει αν η συλλογή αντιπροσώπων είναι κενή. |
| [MulticastDelegate](./multicastdelegate/)() | Δημιουργεί μια κενή συλλογή. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Ισοδύναμο με τον προεπιλεγμένο constructor. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Εκτελεί μια ρηχή αντιγραφή της συλλογής αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Κατασκευαστής μετακίνησης. |
| [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Δημιουργεί μια παρουσία και τοποθετεί τον συγκεκριμένο αντιπρόσωπο στη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)(T) | Δημιουργεί μια παρουσία και τοποθετεί τη συγκεκριμένη τιμή στη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Δημιουργεί μια παρουσία και τοποθετεί τη συγκεκριμένη τιμή στη συλλογή αντιπροσώπων. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Καθορίζει αν η συλλογή αντιπροσώπων δεν είναι κενή. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Καθορίζει αν δύο παρουσίες του MulticastDelegate - το τρέχον αντικείμενο και το συγκεκριμένο αντικείμενο - είναι άνιες. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Καλεί όλους τους αντιπροσώπους που είναι αυτή τη στιγμή στη συλλογή αντιπροσώπων. Οι αντιπρόσωποι καλούνται με την ίδια σειρά με την οποία προστέθηκαν στη συλλογή. Ο τελεστής μπλοκάρει ενώ οι αντιπρόσωποι εκτελούνται. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Προσθέτει τον συγκεκριμένο αντιπρόσωπο στη συλλογή. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Αφαιρεί τον συγκεκριμένο αντιπρόσωπο από τη συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Αναθέτει τη συλλογή των αντιπροσώπων που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο στο τρέχον αντικείμενο. Ως αποτέλεσμα και τα δύο αντικείμενα δείχνουν στην ίδια συλλογή αντιπροσώπων. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Καθορίζει αν η συλλογή αντιπροσώπων είναι κενή. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Καθορίζει αν δύο παρουσίες του MulticastDelegate - το τρέχον αντικείμενο και το συγκεκριμένο αντικείμενο - είναι ίσες. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Καθαρίζει τις περιέχουσες callbacks που είναι κενές (χωρίς πραγματική κλήση). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Επιστρέφει μια αναφορά στο αντικείμενο [TypeInfo](../typeinfo/) που αντιπροσωπεύει τις πληροφορίες τύπου της κλάσης MulticastDelegate. |
| [~MulticastDelegate](./~multicastdelegate/)() | Καταστροφέας. |

## Τύποι

| Τύπος | Περιγραφή |
| --- | --- |
| [Callback](./callback/) | Ο τύπος των αντιπροσώπων που αντιπροσωπεύονται από την κλάση MulticastDelegate. |
| [Function](./function/) | Ο τύπος της συνάρτησης που σχετίζεται με την υπογραφή του αντιπρόσωπου. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)