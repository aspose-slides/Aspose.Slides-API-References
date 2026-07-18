---
title: IExcelDataWorkbook
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει ένα βιβλίο εργασίας που παρέχει πρόσβαση στα δεδομένα Excel για γενική χρήση.
type: docs
weight: 40
url: /el/aspose.slides.excel/iexceldataworkbook/
---
## IExcelDataWorkbook κλάση

Αντιπροσωπεύει ένα βιβλίο εργασίας που παρέχει πρόσβαση στα δεδομένα [Excel](../) για γενική χρήση.

```cpp
class IExcelDataWorkbook : public virtual System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμα κι αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμα κι αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)(**int32_t**, **int32_t**, **int32_t**) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και τις συντεταγμένες του κελιού. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα του και τις συντεταγμένες του κελιού. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)(**int32_t**, [System::String](../../system/string/)) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και το όνομα κελιού σε μορφή Excel (π.χ., "B2"). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), [System::String](../../system/string/)) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα κελιού σε μορφή Excel (π.χ., "B2"). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\>\>\> [GetCells](./getcells/)([System::String](../../system/string/), **bool**) | Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<**int32_t**, [System::String](../../system/string/)\>\> [GetChartsFromWorksheet](./getchartsfromworksheet/)([System::String](../../system/string/)) | Ανακτά ένα λεξικό που περιέχει τους δείκτες και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός βιβλίου εργασίας [Excel](../). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::String](../../system/string/)\>\> [GetWorksheetNames](./getworksheetnames/)() | Ανακτά τα ονόματα όλων των φύλλων εργασίας που περιέχονται στο βιβλίο εργασίας [Excel](../). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλειδώματα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην ουσία, μόνο αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην ουσία, μόνο αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Σύγκριση ανά αναφορά ενός αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση του string και του nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή των δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Excel](../)
* Βιβλιοθήκη [Aspose.Slides](../../)