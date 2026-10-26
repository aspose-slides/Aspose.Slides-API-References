---
title: ILoadOptions
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.
type: docs
weight: 2796
url: /el/aspose.slides/iloadoptions/
---
## ILoadOptions κλάση

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατα τη φόρτωση μιας παρουσίασης.

```cpp
class ILoadOptions : public virtual System::Object
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στο στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στο στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς διαχείρισης Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο πλήθος bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται για τη ρύθμιση του βέλτιστου λόγου απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | Επιστρέφει την ασιατική γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Διαβάζει [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | Επιστρέφει την κανονική γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Διαβάζει [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | Επιστρέφει τη γραμματοσειρά Symbol που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Διαβάζει [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | Επιστρέφει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Διαβάζει [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | Καθορίζει εάν [Aspose.Slides](../) θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | Το διακριτικό για την παρακολούθηση αιτήσεων διακοπής. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | Επιστρέφει τη μορφή μιας παρουσίασης προς φόρτωση. Διαβάζει [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με τη χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή ιδιότητας είναι true, τότε οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα εξαχθεί εξαίρεση. Διαβάζει **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Λαμβάνει τον κωδικό πρόσβασης. Διαβάζει [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | Επιστρέφει τη διεπαφή αντιστροφής κλήσης που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Διαβάζει [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό επιπρόσθετης συμπεριφοράς λογιστικών φύλλων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | Επιστρέφει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Διαβάζει [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση τύπου που περιγράφεται από targetType. Αναλογία του τελεστή 'is' της C#. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέο ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά τη συγκεκριμένη τιμή. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς διαχείρισης Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο πλήθος bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται για τη ρύθμιση του βέλτιστου λόγου απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | Ορίζει την ασιατική γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Γράφει [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | Ορίζει την κανονική γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Γράφει [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | Ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Γράφει [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | Ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Γράφει [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | Καθορίζει εάν [Aspose.Slides](../) θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | Το διακριτικό για την παρακολούθηση αιτήσεων διακοπής. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | Ορίζει τη μορφή μιας παρουσίασης προς φόρτωση. Γράφει [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με τη χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή ιδιότητας είναι true, τότε οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα εξαχθεί εξαίρεση. Γράφει **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Ορίζει τον κωδικό πρόσβασης. Γράφει [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | Ορίζει τη διεπαφή αντιστροφής κλήσης που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Γράφει [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό επιπρόσθετης συμπεριφοράς λογιστικών φύλλων. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Γράφει [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέ φει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδυναμής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδυναμής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Ονομαχώρος [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)