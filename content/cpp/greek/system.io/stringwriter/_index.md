---
title: StringWriter
second_title: Aspose.Slides για C++ Αναφορά API
description: "Υλοποιεί ένα TextWriter που γράφει πληροφορίες σε μια συμβολοσειρά. Τα αντικείμενα αυτής της κλάσης θα πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject() . Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 417
url: /el/system.io/stringwriter/
---
## StringWriter κλάση

Υλοποιεί ένα [TextWriter](../textwriter/) που γράφει πληροφορίες σε μια συμβολοσειρά. Τα αντικείμενα αυτής της κλάσης θα πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Κλείνει τη ροή και απελευθερώνει τους αποκτηθέντες πόρους. |
| void [Dispose](../textwriter/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει τη βασική ροή. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual void [Flush](../textwriter/flush/)() | Αδειάζει το περιεχόμενο του buffer στη βασική ροή. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Επιστρέφει την τρέχουσα κωδικοποίηση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Επιστρέφει το τρέχον αντικείμενο [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Επιστρέφει το τρέχον αντικείμενο [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Επιστρέφει μια συμβολοσειρά τερματιστή γραμμής. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Επιστρέφει μια συμβολοσειρά τερματιστή γραμμής. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Επιστρέφει τον τρέχοντα StringBuilder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογική του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Καταχωρητής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Ορίζει μια συμβολοσειρά τερματιστή γραμμής. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Δημιουργεί μια νέα παρουσία του [StringWriter](./) χρησιμοποιώντας τον καθορισμένο StringBuilder και [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Δημιουργεί μια νέα παρουσία του [StringWriter](./) χρησιμοποιώντας τον καθορισμένο StringBuilder και [IFormatProvider](../../system/iformatprovider/) από την τρέχουσα κουλτούρα. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Δημιουργεί μια νέα παρουσία του [StringWriter](./) χρησιμοποιώντας το καθορισμένο [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Δημιουργεί μια νέα παρουσία του [StringWriter](./) χρησιμοποιώντας [IFormatProvider](../../system/iformatprovider/) από την τρέχουσα κουλτούρα. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Επιστρέφει την υποκείμενη συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Write](./write/)(char_t) override | Γράφει τον καθορισμένο χαρακτήρα στη ροή. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποσύνολο χαρακτήρων από τον καθορισμένο πίνακα χαρακτήρων στη ροή. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Γράφει τη καθορισμένη συμβολοσειρά στη ροή. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου στη ροή. |
| virtual void [Write](../textwriter/write/)(**bool**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης λογικής τιμής στη ροή. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου [Decimal](../../system/decimal/) αντικειμένου στη ροή. |
| virtual void [Write](../textwriter/write/)(**double**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής κινητής υποδιαστολής διπλής ακρίβειας στη ροή. |
| virtual void [Write](../textwriter/write/)(int) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 32-bit ακεραίου στη ροή. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 64-bit ακεραίου στη ροή. |
| virtual void [Write](../textwriter/write/)(**float**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής κινητής υποδιαστολής μονής ακρίβειας στη ροή. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 32-bit άσυμης ακεραίου στη ροή. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 64-bit άσυμης ακεραίου στη ροή. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα στη ροή. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Γράφει τη καθορισμένη συμβολοσειρά C στη ροή. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου [TypeInfo](../../system/typeinfo/) αντικειμένου στη ροή. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με τη καθορισμένη μορφή στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)() | Γράφει χαρακτήρες τερματιστή γραμμής στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης λογικής τιμής, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Γράφει τον καθορισμένο χαρακτήρα, ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου [Decimal](../../system/decimal/) αντικειμένου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής κινητής υποδιαστολής διπλής ακρίβειας, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 32-bit ακεραίου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 64-bit ακεραίου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής κινητής υποδιαστολής μονής ακρίβειας, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Γράφει τη καθορισμένη συμβολοσειρά, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 32-bit άσυμης ακεραίου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Γράφει την αναπαράσταση συμβολοσειράς της καθορισμένης τιμής 64-bit άσυμης ακεραίου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα, ακολουθούμενους από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Γράφει το καθορισμένο υποσύνολο χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων, ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Γράφει τη καθορισμένη συμβολοσειρά C, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου [TypeInfo](../../system/typeinfo/) αντικειμένου, ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Γράφει τις καθορισμένες τιμές μορφοποιημένες σύμφωνα με τη καθορισμένη μορφή, ακολουθούμενες από τους χαρακτήρες τερματισμού γραμμής, στη ροή. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Καταστροφέας. |

## Δείτε επίσης

* Κλάση [TextWriter](../textwriter/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)