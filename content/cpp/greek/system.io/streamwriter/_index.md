---
title: StreamWriter
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει έναν συγγραφέα που γράφει χαρακτήρες σε ένα ρεύμα byte. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργήσετε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 391
url: /el/system.io/streamwriter/
---
## StreamWriter κλάση

Αντιπροσωπεύει έναν συγγραφέα που γράφει χαρακτήρες σε ένα ρεύμα byte. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργήσετε εμφάνιση αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν την κλάση σε έναν δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε στις συναρτήσεις ως όρισμα.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Close](./close/)() override | Κλείνει το ρεύμα και απελευθερώνει τους αποκτηθέντες πόρους. |
| void [Dispose](./dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει το υποκείμενο ρεύμα. |
| virtual void [Dispose](./dispose/)(**bool**) | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει το υποκείμενο ρεύμα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την C# [Object.Equals](../../system/object/equals/) σημασιολογία. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με κανένα τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με κανένα τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Για εσωτερικούς σκοπούς μόνο. |
| void [Flush](./flush/)() override | Αδειάζει το περιεχόμενο της προσωρινής μνήμης στο υποκείμενο ρεύμα και στη συνέχεια αδειάζει το υποκείμενο ρεύμα. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Επιστρέφει μια τιμή που υποδεικνύει αν το [StreamWriter](./) θα αδειάζει τα δεδομένα στο υποκείμενο ρεύμα κάθε φορά που καλείται η μέθοδος [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Επιστρέφει έναν μοιρασμένο δείκτη σε ένα αντικείμενο που αντιπροσωπεύει το υποκείμενο ρεύμα. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Επιστρέφει την τρέχουσα κωδικοποίηση που χρησιμοποιείται. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Επιστρέφει το τρέχον αντικείμενο [IFormatProvider](../../system/iformatprovider/) που χρησιμοποιείται. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Επιστρέφει το τρέχον αντικείμενο [IFormatProvider](../../system/iformatprovider/) που χρησιμοποιείται. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Επιστρέφει μια συμβολοσειρά διαχωριστικού γραμμής. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Επιστρέφει μια συμβολοσειρά διαχωριστικού γραμμής. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Ανάλογο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Ανάλογο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Ανάλογο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Ανάλογο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Επιστρέφει μια τιμή που καθορίζει αν το [StreamWriter](./) θα αδειάζει τα δεδομένα στο υποκείμενο ρεύμα κάθε φορά που καλείται η μέθοδος [StreamWriter::Write](./write/). |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Ορίζει μια συμβολοσειρά διαχωριστικού γραμμής. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](./) που γράφει χαρακτήρες στο καθορισμένο υποκείμενο ρεύμα χρησιμοποιώντας κωδικοποίηση UTF-8 και προσωρινή μνήμη με προεπιλεγμένο μέγεθος 1024 byte. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](./) που γράφει χαρακτήρες στο καθορισμένο υποκείμενο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση και προσωρινή μνήμη με προεπιλεγμένο μέγεθος 1024 byte. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](./) που γράφει χαρακτήρες στο καθορισμένο υποκείμενο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση και μια προσωρινή μνήμη του καθορισμένου μεγέθους. Ένα όρισμα καθορίζει αν το υποκείμενο ρεύμα πρέπει να κλείσει όταν το αντικείμενο [StreamWriter](./) απορριφθεί. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](./) που γράφει χαρακτήρες στο καθορισμένο αρχείο χρησιμοποιώντας κωδικοποίηση UTF-8 και προσωρινή μνήμη με προεπιλεγμένο μέγεθος 1024 byte. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](./) που γράφει χαρακτήρες στο καθορισμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση και μια προσωρινή μνήμη με προεπιλεγμένο μέγεθος 1024 byte. Ένα όρισμα καθορίζει αν τα δεδομένα πρέπει να προσαρτηθούν στο αρχείο ή να το αντικατασταθεί. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](./) που γράφει χαρακτήρες στο καθορισμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση και μέγεθος προσωρινής μνήμης. Ένα όρισμα καθορίζει αν τα δεδομένα πρέπει να προσαρτηθούν στο αρχείο ή να το αντικατασταθεί. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Ανάλογο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την εντολή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Write](./write/)(char_t) override | Γράφει τον καθορισμένο χαρακτήρα στο ρεύμα. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Γράφει την καθορισμένη συμβολοσειρά στο ρεύμα. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου στο ρεύμα. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα στο ρεύμα. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποδιάστημα χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων στο ρεύμα. |
| void [Write](./write/)(const char_t *) override | Γράφει την καθορισμένη συμβολοσειρά C στο ρεύμα. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(**bool**) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης λογικής τιμής στο ρεύμα. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου [Decimal](../../system/decimal/) στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(**double**) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης τιμής κινητής υποδιαστολής διπλής ακρίβειας στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(int) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης τιμής ακέραιου 32-bit στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης τιμής ακέραιου 64-bit στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(**float**) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης τιμής κινητής υποδιαστολής μονής ακρίβειας στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης τιμής ακεραίου χωρίς πρόσημο 32-bit στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Γράφει την συμβολοσειρά αναπαράστασης της καθορισμένης τιμής ακεραίου χωρίς πρόσημο 64-bit στο ρεύμα. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου [TypeInfo](../../system/typeinfo/) στο ρεύμα. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με το καθορισμένο μορφότυπο στο ρεύμα. |
| void [WriteLine](./writeline/)() override | Γράφει χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Γράφει την καθορισμένη συμβολοσειρά ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα ακολουθούμενους από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποδιάστημα χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων ακολουθούμενο από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](./writeline/)(const char_t *) override | Γράφει την καθορισμένη συμβολοσειρά C ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Γράφει την συμβολοσειρά αναπαράστασης της λογικής τιμής ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Γράφει τον καθορισμένο χαρακτήρα ακολουθούμενο από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου [Decimal](../../system/decimal/) ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Γράφει την συμβολοσειρά αναπαράστασης της τιμής κινητής υποδιαστολής διπλής ακρίβειας ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Γράφει την συμβολοσειρά αναπαράστασης της τιμής ακέραιου 32-bit ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Γράφει την συμβολοσειρά αναπαράστασης της τιμής ακέραιου 64-bit ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Γράφει την συμβολοσειρά αναπαράστασης της τιμής κινητής υποδιαστολής μονής ακρίβειας ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Γράφει την συμβολοσειρά αναπαράστασης της τιμής ακεραίου χωρίς πρόσημο 32-bit ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Γράφει την συμβολοσειρά αναπαράστασης της τιμής ακεραίου χωρίς πρόσημο 64-bit ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Γράφει την συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου [TypeInfo](../../system/typeinfo/) ακολουθούμενη από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με το καθορισμένο μορφότυπο ακολουθούμενες από τους χαρακτήρες διαχωριστικού γραμμής στο ρεύμα. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
| [~StreamWriter](./~streamwriter/)() | Καταστροφέας. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Καταστροφέας. |

## Δείτε επίσης

* Κλάση [TextWriter](../textwriter/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)