---
title: BinaryWriter
second_title: "Aspose.Slides για C++ API Αναφορά"
description: "Αντιπροσωπεύει έναν γραφέα που γράφει τιμές πρωτόγονων τύπων σε ρεύμα byte. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject(). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στο στοίβο ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 105
url: /el/system.io/binarywriter/
---
## BinaryWriter κλάση

Αντιπροσωπεύει έναν γραφέα που γράφει τιμές πρωτόγονων τύπων σε ρεύμα byte. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στο στοίβο ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα έλεγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class BinaryWriter : public System::IDisposable
```

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Δημιουργεί μια παρουσία της κλάσης [BinaryWriter](./) που γράφει δεδομένα στο καθορισμένο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |
| void [Close](./close/)() | Κλείνει το τρέχον αντικείμενο [BinaryWriter](./) και το υποκείμενο ρεύμα εξόδου. |
| void [Dispose](./dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει το υποκείμενο ρεύμα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| void [Flush](./flush/)() | Καθαρίζει το ρεύμα εξόδου. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Επιστρέφει το ρεύμα εξόδου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγορίων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγορίων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Ορίζει τη θέση του ρεύματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόμεσο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [Write](./write/)(**uint8_t**) | Γράφει την καθορισμένη μη υπογεγραμμένη ακέραια τιμή 8-bit στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Γράφει το καθορισμένο υποεύρος bytes από τον καθορισμένο πίνακα byte στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Γράφει το καθορισμένο υποεύρος χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**bool**) | Γράφει ένα μεμονωμένο byte με τιμή 0 αν **value** είναι 'true' και 1 αν **value** είναι 'false' στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(char16_t) | Γράφει την καθορισμένη 16-bit χαρακτήρα στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**int16_t**) | Γράφει την καθορισμένη 16-bit ακέραια τιμή στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(int) | Γράφει την καθορισμένη 32-bit ακέραια τιμή στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**int64_t**) | Γράφει την καθορισμένη 64-bit ακέραια τιμή στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**uint16_t**) | Γράφει την καθορισμένη μη υπογεγραμμένη 16-bit ακέραια τιμή στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**uint32_t**) | Γράφει την καθορισμένη μη υπογεγραμμένη 32-bit ακέραια τιμή στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**uint64_t**) | Γράφει την καθορισμένη μη υπογεγραμμένη 64-bit ακέραια τιμή στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**float**) | Γράφει την καθορισμένη τιμή κινητής υποδιαστολής μονής ακρίβειας στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(**double**) | Γράφει την καθορισμένη τιμή κινητής υποδιαστολής διπλής ακρίβειας στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Γράφει την αναπαράσταση byte της καθορισμένης τιμής [Decimal](../../system/decimal/) στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Γράφει μια συμβολοσειρά προεπιλεγμένου μήκους στην τρέχουσα κωδικοποίηση στο ρεύμα εξόδου. |
| virtual void [Write](./write/)(const char_t *) | Γράφει μια συμβολοσειρά προεπιλεγμένου μήκους στην τρέχουσα κωδικοποίηση στο ρεύμα εξόδου. |
|  [~BinaryWriter](./~binarywriter/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)