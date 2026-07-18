---
title: ConsoleOutput
second_title: Aspose.Slides για το API του C++
description: "Αναπαριστά το τυπικό ρεύμα εξόδου. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 209
url: /el/system/consoleoutput/
---
## ConsoleOutput κλάση

Αναπαριστά το τυπικό ρεύμα εξόδου. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Κλείνει το ρεύμα και απελευθερώνει τους αποκτηθέντες πόρους. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει το υποκείμενο ρεύμα. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Αποστέλλει το περιεχόμενο του buffer στο υποκείμενο ρεύμα. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Επιστρέφει πάντα την κωδικοποίηση ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Επιστρέφει το τρέχον χρησιμοποιούμενο [IFormatProvider](../iformatprovider/) αντικείμενο. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Επιστρέφει το τρέχον χρησιμοποιούμενο [IFormatProvider](../iformatprovider/) αντικείμενο. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Επιστρέφει μια συμβολοσειρά διακόπτη γραμμής. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Επιστρέφει μια συμβολοσειρά διακόπτη γραμμής. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αναλογο της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογο της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογο του τελεστή C# 'is'. |
| void [Lock](../object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογο της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τιμής αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστης αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Ορίζει μια συμβολοσειρά διακόπτη γραμμής. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει την n'tη παράμετρο προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστης αναφοράς. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστης αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστης αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Αναλογο της μεθόδου C# [Object.ToString()](../object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Υλοποιεί το ξεκόλλημα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Write](./write/)(**bool**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης της καθορισμένης τιμής bool στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(char_t) override | Εκτυπώνει την καθορισμένη τιμή χαρακτήρα στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)([Decimal](../decimal/)) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης της τιμής [Decimal](../decimal/) στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(**double**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής κινητής υποδιαστολής διπλής ακρίβειας στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(**int32_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής 32-bit ακέραιου στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(**int64_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής 64-bit ακέραιου στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(**float**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής κινητής υποδιαστολής μονής ακρίβειας στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const [String](../string/)\&) override | Εκτυπώνει το καθορισμένο αντικείμενο συμβολοσειράς στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(**uint32_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής μη υπογεγραμμένου 32-bit ακέραιου στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(**uint64_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής μη υπογεγραμμένου 64-bit ακέραιου στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης του καθορισμένου πίνακα χαρακτήρων στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης μιας περιοχής τιμών του καθορισμένου πίνακα χαρακτήρων στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const char_t *) override | Εκτυπώνει τη καθορισμένη c-συμβολοσειρά στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης του καθορισμένου [TypeInfo](../typeinfo/) αντικειμένου στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Γράφει τη συμβολοσειρά αναπαράστασης της καθορισμένης τιμής 32-bit ακέραιου στο ρεύμα. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με τη καθορισμένη μορφή στο ρεύμα. |
| void [WriteLine](./writeline/)() override | Εκτυπώνει τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης του καθορισμένου αντικειμένου ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(**bool**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης της καθορισμένης τιμής bool ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(char_t) override | Εκτυπώνει την καθορισμένη τιμή χαρακτήρα ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης της τιμής [Decimal](../decimal/) ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(**double**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής κινητής υποδιαστολής διπλής ακρίβειας ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(int) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής 32-bit ακέραιου ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(**int64_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής 64-bit ακέραιου ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(**float**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής κινητής υποδιαστολής μονής ακρίβειας ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Εκτυπώνει το καθορισμένο αντικείμενο συμβολοσειράς ακολουθούμενο από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής μη υπογεγραμμένου 32-bit ακέραιου ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης τιμής μη υπογεγραμμένου 64-bit ακέραιου ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης του καθορισμένου πίνακα χαρακτήρων ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης μιας περιοχής τιμών του καθορισμένου πίνακα χαρακτήρων ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const char_t *) override | Εκτυπώνει τη καθορισμένη c-συμβολοσειρά ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Εκτυπώνει τη συμβολοσειρά αναπαράστασης του καθορισμένου [TypeInfo](../typeinfo/) αντικειμένου ακολουθούμενη από τον τρέχοντα διακόπτη γραμμής στο ρεύμα εξόδου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με τη καθορισμένη μορφή ακολουθούμενες από τους χαρακτήρες τερματισμού γραμμής στο ρεύμα. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Καταστροφέας. |

## Δείτε επίσης

* Κλάση [TextWriter](../../system.io/textwriter/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)