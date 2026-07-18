---
title: EnumeratorOfTypeAdapter
second_title: Aspose.Slides για C++ Αναφορά API
description: Enumerator που χρησιμοποιείται από τη μέθοδο επέκτασης IEnumerable.OfType().
type: docs
weight: 66
url: /el/system.collections.generic.details/enumeratoroftypeadapter/
---
## EnumeratorOfTypeAdapter κλάση

Enumerator used by the IEnumerable.OfType() extension method.

```cpp
template<typename Source,typename Result>class EnumeratorOfTypeAdapter : public System::Collections::Generic::IEnumerator<Result>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης των στοιχείων της συλλογής. |
| Result | Ο τύπος αποτελέσματος των στοιχείων της συλλογής. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [IEnumerator](../../system.collections.generic/ienumerator/) * [AsVirtualizedIterator](../../system.collections.generic/ienumerator/asvirtualizediterator/)() | Προετοιμάζει τον iterator για χρήση από την κλάση VirtualizedIterator. |
| System::Details::VirtualizedIteratorBase\<Result\> * [CloneIterator](./cloneiterator/)() const override |  |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../../system.collections.generic/ienumerator/current/)() const | Λαμβάνει το τρέχον στοιχείο. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Δεν κάνει κάτι. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/)([SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<Source\>\>) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με το στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με το στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Result\> [get_Current](./get_current/)() const override | Λαμβάνει το τρέχον στοιχείο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [IEnumerator](../../system.collections.generic/ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../../system.collections.generic/ienumerator/incrementiterator/)() override | Μετακινεί το iterator ένα βήμα εμπρός. |
| void [InitializeIterator](../../system.collections.generic/ienumerator/initializeiterator/)() override | Κάνει την πρώτη κλήση [MoveNext()](../../system.collections.generic/ienumerator/movenext/) και προετοιμάζει το αντικείμενο enumerator για χρήση από το VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../../system.collections.generic/ienumerator/markownedbyvirtualizediterator/)() | Σημειώνει τον enumerator που ανήκει στον virtualized iterator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| **bool** [MoveNext](./movenext/)() override | Μετακινεί τον enumerator στο επόμενο στοιχείο. Αν δεν είχε αναφερθεί κάποιο στοιχείο προηγουμένως, θέτει την αναφορά στο πρώτο διαθέσιμο στοιχείο. Αν έχει φτάσει στο τέλος του container, δεν κάνει τίποτα. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [Reset](./reset/)() override | Επαναφέρει τον enumerator στη θέση πριν το πρώτο στοιχείο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυναμικό δείκτη (ή weak pointer) αντί για κοινόμεσο. Επιτρέπει την αλλαγή δεικτών στα containers σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [~IEnumerator](../../system.collections.generic/ienumerator/~ienumerator/)() |  |
| virtual [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IEnumerator](../../system.collections.generic/ienumerator/)
* Χώρος ονομάτων [System::Collections::Generic::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)