---
title: Object
second_title: Αναφορά API του Aspose.Slides για C++
description: Βασική κλάση που επιτρέπει τη χρήση μεθόδων που είναι διαθέσιμες για την κλάση System.Object σε C#. Όλες οι μη-απλές κλάσεις που χρησιμοποιούνται στο μεταφρασμένο περιβάλλον πρέπει να την κληρονομούν.
type: docs
weight: 1119
url: /el/system/object/
---
## Object class

Βασική κλάση που επιτρέπει τη χρήση μεθόδων που είναι διαθέσιμες για την κλάση [System.Object](./) σε C#. Όλες οι μη-τετριμμένες κλάσεις που χρησιμοποιούνται στο μεταφρασμένο περιβάλλον πρέπει να κληρονομούν αυτήν.

```cpp
class Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στο στυλ C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Επιστρέφει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](./gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική της κλήσης C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Έλεγχος αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογική του τελεστή C# 'is'. |
| void [Lock](./lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](./memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](./object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](./object/)([Object](./) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υπο-κλάσεων. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υπο-κλάσεων. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τιμής αντικείμενο με nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](./referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](./referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](./sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](./tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](./~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι

| Τύπος | Περιγραφή |
| --- | --- |
| [ptr](./ptr/) | Συνώνυμο για τον τύπο έξυπνου δείκτη. |

## Παρατηρήσεις

Πέρα από τις μεθόδους που διατίθενται στην κλάση C# [System.Object](./), επιτρέπει επίσης την υποστήριξη ορισμένων εννοιών ειδικών για το μεταφρασμένο περιβάλλον κώδικα. Αυτό περιλαμβάνει την καταμέτρηση αναφορών που χρησιμοποιείται από τις κλάσεις έξυπνων δεικτών ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) και άλλες υπηρεσίες σχετικές με διαχείριση μνήμης, αποσφαλμάτωση κ.ά.

Κάθε [Object](./) έχει δύο μετρητές αναφοράς: κοινό μετρητή αναφοράς και αδύναμο μετρητή αναφοράς. Ο αδύναμος μετρητής αποθηκεύεται πάντα σε αποσπαστή δομή δεδομένων αντί στο ίδιο το [Object](./), επιτρέποντας στα αδύναμα δείκτες να παραμείνουν μετά το αντικείμενο. Ο έξυπνος μετρητής αποθηκεύεται είτε στο ίδιο το αντικείμενο είτε στην ίδια αποσπαστή δομή, ανάλογα με την κατάσταση του μακροεντολής ENABLE_EXTERNAL_REFCOUNT. Από προεπιλογή, είναι ενεργοποιημένος σε εκδόσεις αποσφαλμάτωσης και απενεργοποιημένος σε εκδόσεις παραγωγής. Εάν ο μετρητής έξυπνου δείκτη αποθηκευτεί στο ίδιο το αντικείμενο, η αποσπαστή δομή δημιουργείται μόνο εάν υπάρχουν αδύναμοι δείκτες προς το αντικείμενο. Διαφορετικά, δημιουργείται μαζί με το αντικείμενο.

Όλοι οι έξυπνοι δείκτες χρησιμοποιούν αυτούς τους δύο μετρητές αναφοράς και συμβάλλουν στην ίδια και μοναδική ομάδα ιδιοκτησίας.

Εάν η υποκλάση [Object](./) δημιουργηθεί στην στοίβα, δεν μπορούν να δημιουργηθούν έξυπνοι δείκτες προς αυτήν· διαφορετικά προκύπτει πρόβλημα διαγραφής στοίβας.

Αυτός ο τύπος μπορεί να εκχωρηθεί είτε στην στοίβα ως τύπο τιμής είτε στο σωρό χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Μόλις το αντικείμενο εκχωρηθεί, μην αναμιγνύετε αυτές τις δύο περιπτώσεις χρήσης: η ύπαρξη δεικτών [SmartPtr](../smartptr/) σε αντικείμενα που εκχωρήθηκαν στην στοίβα απαγορεύεται αυστηρά.

## Δείτε επίσης

* Namespace [System](../)
* Library [Aspose.Slides](../../)