---
title: StringFormat
second_title: Αναφορά API Aspose.Slides για C++
description: "Περιλαμβάνει πληροφορίες διάταξης κειμένου, χειρισμούς εμφάνισης και λειτουργίες OpenType. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να περικλείετε αυτή τη κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν τον δείκτη για τη μεταβίβαση του σε συναρτήσεις ως όρισμα."
type: docs
weight: 313
url: /el/system.drawing/stringformat/
---
## StringFormat κλάση

Περιλαμβάνει πληροφορίες διάταξης κειμένου, χειρισμούς εμφάνισης και λειτουργίες OpenType. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να περικλείετε αυτή τη κλάση σε έναν δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα.

```cpp
class StringFormat : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [Clone](./clone/)() | Επιστρέφει ακριβές αντίγραφο του τρέχοντος αντικειμένου. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [StringAlignment](../stringalignment/) [get_Alignment](./get_alignment/)() const | Επιστρέφει τιμή που υποδηλώνει την οριζόντια στοίχιση της συμβολοσειράς. |
| **int32_t** [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Επιστρέφει τιμή που υποδεικνύει τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται με δυτικά ψηφία. |
| [StringDigitSubstitute](../stringdigitsubstitute/) [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Επιστρέφει τη μέθοδο αντικατάστασης ψηφίων. |
| [StringFormatFlags](../stringformatflags/) [get_FormatFlags](./get_formatflags/)() const | Επιστρέφει έναν δυαδικό συνδυασμό των StringFormatFlags που καθορίζει τη μορφή συμβολοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericDefault](./get_genericdefault/)() | Επιστρέφει ένα αντικείμενο [StringFormat](./) που αντιπροσωπεύει μια γενική προεπιλεγμένη μορφή. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericTypographic](./get_generictypographic/)() | Επιστρέφει ένα αντικείμενο [StringFormat](./) που αντιπροσωπεύει μια γενική τυπογραφική μορφή. |
| [Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/) [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Επιστρέφει την τιμή που υποδεικνύει πώς εμφανίζεται το πρόθεμα του hot key. |
| [StringAlignment](../stringalignment/) [get_LineAlignment](./get_linealignment/)() const | Επιστρέφει τιμή που υποδεικνύει την κάθετη στοίχιση της συμβολοσειράς. |
| [StringTrimming](../stringtrimming/) [get_Trimming](./get_trimming/)() const | Επιστρέφει τιμή που υποδηλώνει πώς περικοπείται η συμβολοσειρά. |
| int [GetCharacterRangesCount](./getcharacterrangescount/)() const | Λαμβάνει το μέγεθος του πίνακα [CharacterRange](../characterrange/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| [ArrayPtr](../../system/arrayptr/)\<**float**\> [GetTabStops](./gettabstops/)(**float**\&) const | Επιστρέφει τα σημεία διαχωρισμού (tab stops) για το τρέχον αντικείμενο [StringFormat](./). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εγκαθιστά το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων των υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο καταμετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Alignment](./set_alignment/)([StringAlignment](../stringalignment/)) | Ορίζει την οριζόντια στοίχιση της συμβολοσειράς. |
| void [set_FormatFlags](./set_formatflags/)([StringFormatFlags](../stringformatflags/)) | Ορίζει τις σημαίες μορφής συμβολοσειράς. |
| void [set_HotkeyPrefix](./set_hotkeyprefix/)([Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/)) | Ορίζει την τιμή που καθορίζει πώς πρέπει να εμφανίζεται το πρόθεμα του hot key. |
| void [set_LineAlignment](./set_linealignment/)([StringAlignment](../stringalignment/)) | Ορίζει την κάθετη στοίχιση της συμβολοσειράς. |
| void [set_Trimming](./set_trimming/)([StringTrimming](../stringtrimming/)) | Ορίζει μια τιμή που καθορίζει πώς περικόπτεται η συμβολοσειρά. |
| void [SetDigitSubstitution](./setdigitsubstitution/)(**int32_t**, [StringDigitSubstitute](../stringdigitsubstitute/)) | Ορίζει τη γλώσσα και τη μέθοδο αντικατάστασης ψηφίων. |
| void [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const [ArrayPtr](../../system/arrayptr/)\<[CharacterRange](../characterrange/)\>\&) | Ορίζει έναν πίνακα αντικειμένων [CharacterRange](../characterrange/) που αντιπροσωπεύουν τα εύρη χαρακτήρων που μετρήθηκαν από κλήση της μεθόδου MeasureCharacterRanges(). |
| void [SetTabStops](./settabstops/)(**float**, const [ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Ορίζει τα σημεία tab για το τρέχον αντικείμενο [StringFormat](./). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-στό στοιχείο πρότυπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου καταμετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο καταμετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο καταμετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [StringFormat](./stringformat/)() | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [StringFormat](./). |
|  [StringFormat](./stringformat/)([StringFormatFlags](../stringformatflags/), **int32_t**) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [StringFormat](./) με τις καθορισμένες σημαίες μορφής και γλώσσα. |
|  [StringFormat](./stringformat/)(const [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\>\&) | Κατασκευαστής αντιγραφής. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εγκαθιστά την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εγκαθιστά το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο καταμετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο καταμετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing](../)
* Βιβλιοθήκη [Aspose.Slides](../../)