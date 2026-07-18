---
title: TextWriter
second_title: Aspose.Slides για το C++ API Αναφορά
description: "Μία βασική κλάση για κλάσεις που αντιπροσωπεύουν γράφτες που γράφουν σειρές χαρακτήρων σε διαφορετικούς προορισμούς. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφαλματα ελέγχου. Πάντα τυλίξτε αυτή την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 443
url: /el/system.io/textwriter/
---
## TextWriter κλάση

Μια βασική κλάση για κλάσεις που αντιπροσωπεύουν γράφτες που γράφουν σειρές χαρακτήρων σε διαφορετικούς προορισμούς. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε υπόδειγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφαλματα ελέγχου. Πάντα τυλίξτε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class TextWriter : public System::IDisposable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [Close](./close/)() | Κλείνει το stream και απελευθερώνει τους αποκτηθέντες πόρους. |
| void [Dispose](./dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει το υποκείμενο stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσες, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσες, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual void [Flush](./flush/)() | Αδειάζει το περιεχόμενο της ενδιάμεσης μνήμης προς το υποκείμενο stream. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Επιστρέφει την τρέχουσα κωδικοποίηση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Επιστρέφει το τρέχον αντικείμενο [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Επιστρέφει το τρέχον αντικείμενο [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Επιστρέφει μια συμβολοσειρά τερματισμού γραμμής. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Επιστρέφει μια συμβολοσειρά τερματισμού γραμμής. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την παραγωγή κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδώματος της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκλάσεων με αντιγραφή. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσ/operator ανάθεσης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκλάσεων με αντιγραφή. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα βάσει αναφοράς. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα βάσει αναφοράς. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Ορίζει μια συμβολοσειρά τερματισμού γραμμής. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου στο stream. |
| virtual void [Write](./write/)(**bool**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης boolean τιμής στο stream. |
| virtual void [Write](./write/)(char_t) | Γράφει τον καθορισμένο χαρακτήρα στο stream. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου [Decimal](../../system/decimal/) στο stream. |
| virtual void [Write](./write/)(**double**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής διπλής κινητής υποδιαστολής στο stream. |
| virtual void [Write](./write/)(int) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης 32-bit ακέραιας τιμής στο stream. |
| virtual void [Write](./write/)(**int64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης 64-bit ακέραιας τιμής στο stream. |
| virtual void [Write](./write/)(**float**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής κινητής υποδιαστολής μονής ακρίβειας στο stream. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Γράφει τη καθορισμένη συμβολοσειρά στο stream. |
| virtual void [Write](./write/)(**uint32_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης χωρίς πρόσημο 32-bit ακέραιας τιμής στο stream. |
| virtual void [Write](./write/)(**uint64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης χωρίς πρόσημο 64-bit ακέραιας τιμής στο stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα στο stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Γράφει το καθορισμένο υπο-εύρος χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων στο stream. |
| virtual void [Write](./write/)(const char_t *) | Γράφει το καθορισμένο c-string στο stream. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου [TypeInfo](../../system/typeinfo/) στο stream. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με το καθορισμένο πρότυπο στο stream. |
| virtual void [WriteLine](./writeline/)() | Γράφει χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(**bool**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης boolean τιμής ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(char_t) | Γράφει τον καθορισμένο χαρακτήρα ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου [Decimal](../../system/decimal/) ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(**double**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής διπλής κινητής υποδιαστολής ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(int) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης 32-bit ακέραιας τιμής ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης 64-bit ακέραιας τιμής ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(**float**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής κινητής υποδιαστολής μονής ακρίβειας ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Γράφει τη καθορισμένη συμβολοσειρά ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης χωρίς πρόσημο 32-bit ακέραιας τιμής ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης χωρίς πρόσημο 64-bit ακέραιας τιμής ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα ακολουθούμενοι από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Γράφει το καθορισμένο υπο-εύρος χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Γράφει το καθορισμένο c-string ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου [TypeInfo](../../system/typeinfo/) ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με το καθορισμένο πρότυπο ακολουθούμενες από τους χαρακτήρες τερματισμού γραμμής στο stream. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
| virtual  [~TextWriter](./~textwriter/)() | Καταστροφέας. |

## Ορισμοί τύπων

| Ορισμός | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για έναν κοινόχρηστο δείκτη σε αυτήν την κλάση. |

## Δείτε επίσης

* Κλάση [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)