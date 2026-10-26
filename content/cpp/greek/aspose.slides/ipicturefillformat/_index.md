---
title: IPictureFillFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά ένα στυλ γεμίσματος εικόνας.
type: docs
weight: 3225
url: /el/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat κλάση

Αναπαριστά ένα στυλ γεμίσματος εικόνας.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Διαγράφει τις περικομμένες περιοχές του γεμίσματος [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Επιστρέφει το ποσοστό του πραγματικού ύψους της εικόνας που είναι περικομμένο στο κάτω μέρος της εικόνας. Ανάγνωση **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Επιστρέφει το ποσοστό του πραγματικού πλάτους της εικόνας που είναι περικομμένο στο αριστερό μέρος της εικόνας. Ανάγνωση **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Επιστρέφει το ποσοστό του πραγματικού πλάτους της εικόνας που είναι περικομμένο στο δεξιό μέρος της εικόνας. Ανάγνωση **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Επιστρέφει το ποσοστό του πραγματικού ύψους της εικόνας που είναι περικομμένο στο πάνω μέρος της εικόνας. Ανάγνωση **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Επιστρέφει το dpi που χρησιμοποιείται για το γέμισμα εικόνας. Ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Επιστρέφει την εικόνα. Μόνο για ανάγνωση [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Επιστρέφει τη λειτουργία γεμίσματος εικόνας. Ανάγνωση [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Επιστρέφει το κάτω άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το κάτω άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Ανάγνωση **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Επιστρέφει το αριστερό άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το αριστερό άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Ανάγνωση **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Επιστρέφει το δεξιό άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το δεξιό άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Ανάγνωση **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Επιστρέφει το πάνω άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το πάνω άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Ανάγνωση **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Επιστρέφει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου υφής και τον τρόπο επανάληψής του στο σχήμα. Ανάγνωση [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Αναστρέφει το τεμάχιο της υφής γύρω από την οριζόντια, κάθετη ή και τις δύο άξονες. Ανάγνωση [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Επιστρέφει την οριζόντια μετατόπιση της υφής από την αρχή του σχήματος σε μονάδες points. Θετική τιμή μετακινεί την υφή προς τα δεξιά, αρνητική προς τα αριστερά. Ανάγνωση **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Επιστρέφει την κάθετη μετατόπιση της υφής από την αρχή του σχήματος σε μονάδες points. Θετική τιμή μετακινεί την υφή προς τα κάτω, αρνητική προς τα πάνω. Ανάγνωση **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Επιστρέφει την οριζόντια κλίμακα του γεμίσματος υφής ως ποσοστό. Ανάγνωση **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Επιστρέφει την κάθετη κλίμακα του γεμίσματος υφής ως ποσοστό. Ανάγνωση **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια υπόδειξη τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Κλήση απευθείας ή χρήση του αντικειμένου προστασίας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάσεων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τιμής αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται στο κάτω μέρος της εικόνας. Εγγραφή **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται στο αριστερό μέρος της εικόνας. Εγγραφή **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται στο δεξιό μέρος της εικόνας. Εγγραφή **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται στο πάνω μέρος της εικόνας. Εγγραφή **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Ορίζει το dpi που χρησιμοποιείται για το γέμισμα εικόνας. Εγγραφή **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Ορίζει τη λειτουργία γεμίσματος εικόνας. Εγγραφή [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Ορίζει το κάτω άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το κάτω άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Εγγραφή **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Ορίζει το αριστερό άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το αριστερό άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Εγγραφή **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Ορίζει το δεξιό άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το δεξιό άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Εγγραφή **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Ορίζει το πάνω άκρο του γεμιστικού ορθογωνίου που ορίζεται από ποσοστιαία μετατόπιση από το πάνω άκρο του περιοριστικού πλαισίου του σχήματος. Θετικό ποσοστό ορίζει εσωτερική απόσταση, αρνητικό ποσοστό εξωτερική απόσταση. Εγγραφή **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου υφής και τον τρόπο επανάληψής του στο σχήμα. Εγγραφή [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Αναστρέφει το τεμάχιο της υφής γύρω από την οριζόντια, κάθετη ή και τις δύο άξονες. Εγγραφή [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Ορίζει την οριζόντια μετατόπιση της υφής από την αρχή του σχήματος σε μονάδες points. Θετική τιμή μετακινεί την υφή προς τα δεξιά, αρνητική προς τα αριστερά. Εγγραφή **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Ορίζει την κάθετη μετατόπιση της υφής από την αρχή του σχήματος σε μονάδες points. Θετική τιμή μετακινεί την υφή προς τα κάτω, αρνητική προς τα πάνω. Εγγραφή **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Ορίζει την οριζόντια κλίμακα του γεμίσματος υφής ως ποσοστό. Εγγραφή **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Ορίζει την κάθετη κλίμακα του γεμίσματος υφής ως ποσοστό. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση απευθείας ή χρήση του αντικειμένου προστασίας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IFillParamSource](../ifillparamsource/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)