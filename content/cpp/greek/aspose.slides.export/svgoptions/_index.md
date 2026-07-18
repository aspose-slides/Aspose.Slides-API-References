---
title: SVGOptions
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά επιλογές SVG.
type: docs
weight: 703
url: /el/aspose.slides.export/svgoptions/
---
## SVGOptions κλάση

Αντιπροσωπεύει επιλογές SVG.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητών σημείων σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητών σημείων σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Επιστρέφει προεπιλεγμένες ρυθμίσεις. Μόνο-για-ανάγνωση [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Διαβάζει [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Μια λογική σημαία δείχνει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα μέρη θα αφαιρεθούν· εάν είναι false, θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Λαμβάνει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση λιγκουρών. Όταν οριστεί σε **true**, οι λιγκουρές θα απενεργοποιηθούν στην έξοδο απόδοσης. Από προεπιλογή, αυτή η ιδιότητα είναι **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού περιθωρίων για δείκτες. Η μηχανή εγγραφής SVG [Aspose.Slides](../../aspose.slides/) έχει παράκαμψη για αυτό το πρόβλημα: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί τέτοια συμπεριφορά. Ανάγνωση **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Επιστρέφει το οπτικό στυλ του gradient. Ανάγνωση [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων [Ink](../../aspose.slides.ink/) στο εξαγόμενο έγγραφο. Μόνο-για-ανάγνωση [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Επιστρέφει το όριο χαμηλότερης ανάλυσης για rasterization μετααρχείου. Ανάγνωση **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Αναπαριστά το επίπεδο συμπίεσης εικόνων |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Αναπαριστά ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Επιστρέφει ρυθμίσεις για τη δημιουργία του απλούστερου και μικρότερου αρχείου SVG. Μόνο-για-ανάγνωση [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Καθορίζει αν θα παραλείπεται οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Καθορίζει αν θα πραγματοποιηθεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Επιστρέφει ρυθμίσεις για τη δημιουργία του πιο ακριβούς αρχείου SVG. Μόνο-για-ανάγνωση [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος της C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογική του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την δήλωση κλειδώματος lock() της C#. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο στέγης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά ένα αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Γράφει [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Μια λογική σημαία δείχνει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα μέρη θα αφαιρεθούν· εάν είναι false, θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Γράψτε **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς λιγκουρές. Όταν οριστεί σε **true**, οι λιγκουρές θα απενεργοποιηθούν στην έξοδο απόδοσης. Από προεπιλογή, αυτή η ιδιότητα είναι **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Γράψτε **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού περιθωρίων για δείκτες. Η μηχανή εγγραφής SVG [Aspose.Slides](../../aspose.slides/) έχει παράκαμψη για αυτό το πρόβλημα: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει δείκτες. Αυτή η επιλογή απενεργοποιεί τη συμπεριφορά. Γράψτε **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Γράψτε [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ορίζει το οπτικό στυλ του gradient. Γράψτε [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Γράψτε **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Ορίζει το όριο χαμηλότερης ανάλυσης για rasterization μετααρχείου. Γράψτε **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Αναπαριστά το επίπεδο συμπίεσης εικόνων |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Αναπαριστά ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Γράψτε [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Καθορίζει αν θα παραλείπεται οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Καθορίζει αν θα πραγματοποιηθεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Καθορίζει αν το κείμενο σε διαφάνεια θα αποθηκευτεί ως γραφικά. Γράψτε **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Γράψτε [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα του προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να καλείται απ' ευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να καλείται απ' ευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SVGOptions](./) καθορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμου. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος της C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη σύνταξη C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο στέγης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να καλείται απ' ευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να καλείται απ' ευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [SaveOptions](../saveoptions/)
* Κλάση [ISVGOptions](../isvgoptions/)
* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)