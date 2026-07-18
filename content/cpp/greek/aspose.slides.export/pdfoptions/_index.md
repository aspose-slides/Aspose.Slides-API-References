---
title: PdfOptions
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.
type: docs
weight: 573
url: /el/aspose.slides.export/pdfoptions/
---
## PdfOptions κλάση

Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοιχτεί με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Επιστρέφει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών που ορίζονται από το χρήστη και που το [Aspose.Slides](../../aspose.slides/) θα πρέπει να θεωρεί κοινά. Διαβάστε [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Δείχνει εάν πρέπει να επιλέγεται αυτόματα η πιο αποδοτική συμπίεση (αντί της προεπιλογής) για κάθε εικόνα. Εάν οριστεί σε **bool**.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, οδηγώντας σε μικρότερο μέγεθος του τελικού PDF εγγράφου. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο PDF έγγραφο. Διαβάστε [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγή γραμματοσειράς. Διαβάζει [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Αληθής για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Διαβάστε **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Καθορίζει εάν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο ένα υποσύνολο. Διαβάστε **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Καθορίζει εάν το [Aspose.Slides](../../aspose.slides/) θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). [Fonts](../../aspose.slides/fonts/) για κωδικούς χαρακτήρων μεγαλύτερους των 127 είναι πάντα ενσωματωμένοι. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και επιπλέον γραμματοσειρές που ορίζονται από το χρήστη. Διαβάστε **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Επιστρέφει το οπτικό στυλ της διαβάθμισης. Διαβάστε [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | Αληθής για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. Διαβάστε **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων [Ink](../../aspose.slides.ink/) στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Επιστρέφει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο PDF έγγραφο. Διαβάστε **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Ορισμός κωδικού χρήστη για προστασία του PDF εγγράφου. Διαβάστε [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Αντιπροσωπεύει ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Δείχνει εάν το κείμενο πρέπει να ραστραριστεί ως bitmap και να αποθηκευτεί στο PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονο στυλ. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές. Διαβάστε **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Αληθής για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Διαβάστε **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Καθορίζει εάν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Διαβάστε **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Λαμβάνει τη λειτουργία κατά την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Επιστρέφει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο PDF έγγραφο. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. Διαβάστε [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Διαβάστε [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκατηγορίες. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκατηγορίες. |
|  [PdfOptions](./pdfoptions/)() | Κατασκευαστής προεπιλογής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά ενός αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοιχτεί με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών που ορίζονται από το χρήστη και που το [Aspose.Slides](../../aspose.slides/) θα πρέπει να θεωρεί κοινά. Γράψτε [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Δείχνει εάν πρέπει να επιλέγεται αυτόματα η πιο αποδοτική συμπίεση (αντί της προεπιλογής) για κάθε εικόνα. Εάν οριστεί σε **bool**.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, οδηγώντας σε μικρότερο μέγεθος του τελικού PDF εγγράφου. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο PDF έγγραφο. Γράψτε [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ορίζει τη γραμματοσειρά που θα χρησιμοποιηθεί εάν δεν βρεθεί η πηγή γραμματοσειράς. Γράφει [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Αληθής για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Γράψτε **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Καθορίζει εάν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο ένα υποσύνολο. Γράψτε **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Καθορίζει εάν το [Aspose.Slides](../../aspose.slides/) θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). [Fonts](../../aspose.slides/fonts/) για κωδικούς χαρακτήρων μεγαλύτερους των 127 είναι πάντα ενσωματωμένοι. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και επιπλέον γραμματοσειρές που ορίζονται από το χρήστη. Γράψτε **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ορίζει το οπτικό στυλ της διαβάθμισης. Γράψτε [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Ορίζει το διαφανές χρώμα της εικόνας. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | Αληθής για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. Γράψτε **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο PDF έγγραφο. Γράψτε **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Ορισμός κωδικού χρήστη για προστασία του PDF εγγράφου. Γράψτε [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Αντιπροσωπεύει ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Δείχνει εάν το κείμενο πρέπει να ραστραριστεί ως bitmap και να αποθηκευτεί στο PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονο στυλ. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές. Γράψτε **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Αληθής για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Γράψτε **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Καθορίζει εάν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Ορίζει τη λειτουργία κατά την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο PDF έγγραφο. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. Γράψτε [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Γράψτε [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα του προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινού μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με προσαρμοσμένες επιλογές. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Δημιουργεί την κλάση PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Ορίζει την ποιότητα Jpeg
pdfOptions->set_JpegQuality(90);
// Ορίζει τη συμπεριφορά για τα μετααρχεία
pdfOptions->set_SaveMetafilesAsPng(true);
// Ορίζει το επίπεδο συμπίεσης κειμένου
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Καθορίζει το πρότυπο PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Αποθηκεύει την παρουσίαση ως PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με κρυφές διαφάνειες. 
```cpp
// Αρχικοποιεί μια κλάση Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Αρχικοποιεί την κλάση PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Προσθέτει κρυφές διαφάνειες
pdfOptions->set_ShowHiddenSlides(true);
// Αποθηκεύει την παρουσίαση ως PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με κωδικό πρόσβασης. 
```cpp
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Ορίζει τον κωδικό πρόσβασης PDF και τις άδειες πρόσβασης
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Αποθηκεύει την παρουσίαση ως PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με σημειώσεις. 
```cpp
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Ορισμός τύπου και μεγέθους διαφάνειας
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Κλάση [SaveOptions](../saveoptions/)
* Κλάση [IPdfOptions](../ipdfoptions/)
* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)