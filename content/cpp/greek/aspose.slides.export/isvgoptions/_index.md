---
title: ISVGOptions
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναπαριστά επιλογές SVG.
type: docs
weight: 404
url: /el/aspose.slides.export/isvgoptions/
---
## ISVGOptions κλάση

Αναπαριστά επιλογές SVG.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ισοδύναμα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ισοδύναμα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί. Διαβάζει [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Ένα λογικό σημείο δείχνει εάν τα περικομμένα τμήματα παραμένουν μέρος του εγγράφου. Εάν true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν false θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο σε SVG. Ανάγνωση **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων χαρακτήρων. Όταν οριστεί σε **true**, οι συνδέσεις θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | Το SVG 1.1 δεν υποστηρίζει ορισμό εσοχών για markers. [Aspose.Slides](../../aspose.slides/) η μηχανή εγγραφής SVG έχει παράκαμψη: περικόπτει το τέλος της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τα markers. Αυτή η επιλογή απενεργοποιεί τη συμπεριφορά. Ανάγνωση **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Καθορίζει τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Επιστρέφει το οπτικό στυλ του gradient. Ανάγνωση [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων [Ink](../../aspose.slides.ink/) στο εξαγόμενο έγγραφο. Μόνο-ανάγνωση [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Επιστρέφει το κατώτερο όριο ανάλυσης για rasterization μετααρχείων. Ανάγνωση **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Αναπαριστά το επίπεδο συμπίεσης των εικόνων. Ανάγνωση [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Αναπαριστά ένα αντικείμενο κλήσης επιστροφής για αποθήκευση προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Επιστρέφει και ορίζει μια διεπαφή κλήσης επιστροφής που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Καθορίζει εάν θα παραλειφθούν σύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι **true**. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Επιστρέφει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια εμφάνιση τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση C# lock() για κλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί. Γράφει [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Ένα λογικό σημαία υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν μέρος του εγγράφου. Εάν true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν false θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Εγγραφή **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο σε SVG. Εγγραφή **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων χαρακτήρων. Όταν οριστεί σε **true**, οι συνδέσεις θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Εγγραφή **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | Το SVG 1.1 δεν υποστηρίζει ορισμό εσοχών για markers. [Aspose.Slides](../../aspose.slides/) η μηχανή εγγραφής SVG έχει παράκαμψη: περικόπτει το τέλος της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τα markers. Αυτή η επιλογή απενεργοποιεί τη συμπεριφορά. Εγγραφή **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Καθορίζει τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Εγγραφή [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Ορίζει το οπτικό στυλ του gradient. Εγγραφή [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Εγγραφή **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Ορίζει το κατώτερο όριο ανάλυσης για rasterization μετααρχείων. Εγγραφή **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων. Εγγραφή [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Αναπαριστά ένα αντικείμενο κλήσης επιστροφής για αποθήκευση προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Επιστρέφει και ορίζει μια διεπαφή κλήσης επιστροφής που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Εγγραφή [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Καθορίζει εάν θα παραλειφθούν σύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση. Εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **true**. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Εγγραφή **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Εγγραφή [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμής δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη συνταγή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση C# lock() για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμής μετρητή. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμής μετρητή. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ISaveOptions](../isaveoptions/)
* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)