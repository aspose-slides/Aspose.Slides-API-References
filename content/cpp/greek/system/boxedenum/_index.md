---
title: BoxedEnum
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει τη διατυπωμένη (boxed) τιμή απαρίθμησης. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assertion. Πάντα τυλίξτε αυτή την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 92
url: /el/system/boxedenum/
---
## BoxedEnum κλάση

Αντιπροσωπεύει τη διατυπωμένη (boxed) τιμή απαρίθμησης. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assertion. Πάντα να τυλίγετε αυτή την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| E | Τύπος της τιμής απαρίθμησης |
| UT | Ο υποκείμενος τύπος της απαρίθμησης **E** |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | Δημιουργεί μια παρουσία που αντιπροσωπεύει την καθορισμένη τιμή απαρίθμησης. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί το κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | Επιστρέφει την τιμή που αντιπροσωπεύει τον τύπο της διατυπωμένης τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Μετατρέπει την τιμή της διατυπωμένης σταθεράς απαρίθμησης σε 64-ψηφιο ακέραιο. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει μία διατυπωμένη τιμή τύπου enum. |
| void [Lock](../object/lock/)() | Υλοποιεί τη λογοκρισία της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουράς [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλά αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκλάσεων. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλά αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκλάσεων. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Διατυπώνει (boxes) την τιμή της σταθεράς απαρίθμησης του καθορισμένου enum με το καθορισμένο όνομα. Ένα παράμετρος καθορίζει αν η διάκριση πεζών/κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία της συμβολοσειράς που ορίζει το όνομα της σταθεράς απαρίθμησης. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Διατυπώνει την τιμή της σταθεράς απαρίθμησης του καθορισμένου enum με το καθορισμένο όνομα. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)() const override | Μετατρέπει τη διατυπωμένη τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο σε συμβολοσειρά. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Μετατρέπει το διατυπωμένο αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά μορφής. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουράς [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BoxedValue](../boxedvalue/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)