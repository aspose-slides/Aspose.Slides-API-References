---
title: MarkdownSaveOptions
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεύει επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.
type: docs
weight: 547
url: /el/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions κλάση


Αντιπροσωπεύει επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν ισούται με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν ισούται με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται όταν η πηγαία γραμματοσειρά δεν βρεθεί. Διαβάζει [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Επιστρέφει το οπτικό στυλ της διαβάθμισης. Διαβάζει [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Καθορίζει πώς θα αντιμετωπίζονται οι επαναλαμβανόμενοι χαρακτήρες κανονικού κενό κατά την εξαγωγή σε Markdown. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Καθορίζει το όνομα φακέλου για αποθήκευση εικόνων. Η προεπιλογή είναι **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Καθορίζει αν το δημιουργούμενο έγγραφο πρέπει να έχει νέες γραμμές \r (Macintosh) ή \n (Unix) ή \r\n (Windows). Η προεπιλογή είναι **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Αναπαριστά ένα αντικείμενο επαναφοράς (callback) για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Εάν οριστεί σε **true**, αφαιρεί κενές ή μόνο λευκά διαστήματα γραμμές από το τελικό αποτέλεσμα Markdown. Η προεπιλογή είναι **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Καθορίζει αν το δημιουργούμενο έγγραφο θα εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Καθορίζει αν το δημιουργούμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Καθορίζει αν το δημιουργούμενο έγγραφο θα εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Καθορίζει αν θα παραλείπονται υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Διαβάζει **bool**. Η προεπιλογή είναι **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Λαμβάνει τη συμβολοσειρά μορφής που χρησιμοποιείται για επικεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το «{0}» σύμβολο κράτησης, το οποίο θα αντικατασταθεί με το δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: «# Slide {0}» θα παραγάγει «# Slide 1», «# Slide 2» κ.λπ. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Διαβάζει [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αποτελεί ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# «is». |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση C# lock() κλειδώνοντας. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | Constructor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τιμής με αναφορά σε nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν η πηγαία γραμματοσειρά δεν βρεθεί. Γράφει [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ορίζει το οπτικό στυλ της διαβάθμισης. Γράφει [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Καθορίζει πώς θα αντιμετωπίζονται οι επαναλαμβανόμενοι χαρακτήρες κανονικού κενό κατά την εξαγωγή σε Markdown. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Καθορίζει το όνομα φακέλου για αποθήκευση εικόνων. Η προεπιλογή είναι **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Καθορίζει αν το δημιουργούμενο έγγραφο θα έχει νέες γραμμές \r (Macintosh) ή \n (Unix) ή \r\n (Windows). Η προεπιλογή είναι **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Αναπαριστά ένα αντικείμενο επαναφοράς (callback) για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Εάν οριστεί σε **true**, αφαιρεί κενές ή μόνο λευκά διαστήματα γραμμές από το τελικό αποτέλεσμα Markdown. Η προεπιλογή είναι **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Καθορίζει αν το δημιουργούμενο έγγραφο θα εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Καθορίζει αν το δημιουργούμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Καθορίζει αν το δημιουργούμενο έγγραφο θα εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Καθορίζει αν θα παραλείπονται υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράφει **bool**. Η προεπιλογή είναι **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για επικεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το «{0}» σύμβολο κράτησης, το οποίο θα αντικατασταθεί με το δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: «# Slide {0}» θα παράγει «# Slide 1», «# Slide 2», κ.λπ. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Γράφει [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δομές δεδομένων σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση C# lock() αποπλεκομούγοντας. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι ορισμού

| Typedef | Description |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Καλείται για κάθε εικόνα που δεν είναι SVG (bitmap ή metafile) κατά την εξαγωγή σε Markdown. Επιστρέφει **true** για χρήση του καθορισμένου *link*, ή **false** για εφαρμογή της προεπιλεγμένης λογικής αποθήκευσης. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Καλείται για κάθε εικόνα SVG κατά την εξαγωγή σε Markdown. Επιστρέφει **true** για χρήση του καθορισμένου *link*, ή **false** για εφαρμογή της προεπιλεγμένης λογικής αποθήκευσης. |

## Σχόλια


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Δείτε επίσης

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)