---
title: XpsOptions
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή XPS.
type: docs
weight: 807
url: /el/aspose.slides.export/xpsoptions/
---
## XpsOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή XPS.

```cpp
class XpsOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IXpsOptions
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται στην περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Διαβάζει [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Αληθές για να σχεδιάσει μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Διαβάστε **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Επιστρέφει το οπτικό στυλ της διαβάθμισης. Διαβάζει [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Αντιπροσωπεύει ένα αντικείμενο επανάκλησης για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Αληθές για να μετατρέπει όλα τα μετααρχεία που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Διαβάστε **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Προεπιλογή είναι **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Καθορίζει εάν θα παραλειφθούν υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Διαβάστε **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα τερματιστεί. Διαβάζετε [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Ανάλογο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Ανάλογο του κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Ανάλογο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή κλειδώματος C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Ανάλογο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr με αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ορίζει τη γραμματοσειρά που χρησιμοποιείται στην περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Γράφει [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Αληθές για να σχεδιάσει μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Γράψτε **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ορίζει το οπτικό στυλ της διαβάθμισης. Γράψτε [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Αντιπροσωπεύει ένα αντικείμενο επανάκλησης για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Αληθές για να μετατρέπει όλα τα μετααρχεία που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Γράψτε **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Προεπιλογή είναι **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Καθορίζει εάν θα παραλειφθούν υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα τερματιστεί. Γράψτε [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Ανάλογο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [XpsOptions](./xpsoptions/)() | Κατασκευαστής χωρίς παράμετρους. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε παρουσιάσεις σε XPS χρησιμοποιώντας τις προεπιλεγμένες ρυθμίσεις.  
```cpp
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"Convert_XPS.pptx");

// Αποθήκευση της παρουσίασης σε έγγραφο XPS
pres->Save(u"XPS_Output_Without_XPSOption_out.xps", SaveFormat::Xps);
```
Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε παρουσιάσεις σε XPS χρησιμοποιώντας προσαρμοσμένες ρυθμίσεις.  
```cpp
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"Convert_XPS_Options.pptx");

// Δημιουργία της κλάσης TiffOptions
System::SharedPtr<XpsOptions> options = System::MakeObject<XpsOptions>();
// Αποθήκευση των MetaFiles ως PNG
options->set_SaveMetafilesAsPng(true);
// Αποθήκευση της παρουσίασης σε έγγραφο XPS
pres->Save(u"XPS_With_Options_out.xps", SaveFormat::Xps, options);
```

## Δείτε επίσης

* Κλάση [SaveOptions](../saveoptions/)
* Κλάση [IXpsOptions](../ixpsoptions/)
* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)