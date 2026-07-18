---
title: ISwfOptions
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή SWF.
type: docs
weight: 469
url: /el/aspose.slides.export/iswfoptions/
---
## ISwfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Διαβάζει [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Επιστρέφει το οπτικό στυλ του gradient. Διαβάζει [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Καθορίζει την ποιότητα των εικόνων JPEG.\n\n Η προεπιλογή είναι 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Εικόνα που θα εμφανίζεται ως λογότυπο στην πάνω δεξιά γωνία του προβολέα.\n\n Η εικόνα πρέπει να είναι PNG 32x64 εικονοστοιχεία, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Λαμβάνει τη διεύθυνση του πλήρους υπερσυνδέσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Αντιπροσωπεύει ένα αντικείμενο callback για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Εμφάνιση/απόκρυψη του κάτω πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Εμφάνιση/απόκρυψη του πλήκτρου πλήρους οθόνης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Εμφάνιση/απόκρυψη του αριστερού πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Καθορίζει εάν το περίγραμμα γύρω από τις σελίδες θα εμφανίζεται. Η προεπιλογή είναι true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Εμφάνιση/απόκρυψη του βήματος σελίδας. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Εμφάνιση/απόκρυψη της ενότητας αναζήτησης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Εμφάνιση/απόκρυψη ολόκληρου του άνω πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Καθορίζει εάν θα παραβλεφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Διαβάζει **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Λαμβάνει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../islideslayoutoptions/). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Έναρξη με ανοιχτό αριστερό πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Καθορίζει εάν το παραγόμενο έγγραφο SWF θα περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. Η προεπιλογή είναι **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Επιστρέφει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Διαβάζει [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με αναφορά σε nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Ορίζει τη γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Γράφει [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Ορίζει το οπτικό στυλ του gradient. Γράφει [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Καθορίζει την ποιότητα των εικόνων JPEG.\n\n Η προεπιλογή είναι 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Εικόνα που θα εμφανίζεται ως λογότυπο στην πάνω δεξιά γωνία του προβολέα.\n\n Η εικόνα πρέπει να είναι PNG 32x64 εικονοστοιχεία, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Ορίζει τη διεύθυνση του πλήρους υπερσυνδέσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Αντιπροσωπεύει ένα αντικείμενο callback για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Εμφάνιση/απόκρυψη του κάτω πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Εμφάνιση/απόκρυψη του πλήκτρου πλήρους οθόνης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Εμφάνιση/απόκρυψη του αριστερού πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Καθορίζει εάν το περίγραμμα γύρω από τις σελίδες θα εμφανίζεται. Η προεπιλογή είναι true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Εμφάνιση/απόκρυψη του βήματος σελίδας. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Εμφάνιση/απόκρυψη της ενότητας αναζήτησης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Εμφάνιση/απόκρυψη ολόκληρου του άνω πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Καθορίζει εάν θα παραβλεφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράφει **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../islideslayoutoptions/). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Έναρξη με ανοιχτό αριστερό πάνελ. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Καθορίζει εάν το παραγόμενο έγγραφο SWF θα περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. Η προεπιλογή είναι **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Γράφει [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ISaveOptions](../isaveoptions/)
* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)