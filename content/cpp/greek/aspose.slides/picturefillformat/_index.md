---
title: PictureFillFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει ένα στυλ γεμίσματος εικόνας.
type: docs
weight: 4720
url: /el/aspose.slides/picturefillformat/
---
## PictureFillFormat κλάση

Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένα περιοχές. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένα περιοχές. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Διαγράφει τις περικομμένα περιοχές της γεμίσματος [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με το καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού ύψους εικόνας που περικόπτεται από το κάτω μέρος της εικόνας. Ανάγνωση **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού πλάτους εικόνας που περικόπτεται από το αριστερό μέρος της εικόνας. Ανάγνωση **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού πλάτους εικόνας που περικόπτεται από το δεξί μέρος της εικόνας. Ανάγνωση **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού ύψους εικόνας που περικόπτεται από το πάνω μέρος της εικόνας. Ανάγνωση **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Επιστρέφει τα dpi που χρησιμοποιούνται για τη γεμίσματος μιας εικόνας. Ανάγνωση **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει τον γονέα [IPresentationComponent](../ipresentationcomponent/). Μόνο-ανάγωση [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Επιστρέφει την εικόνα. Μόνο-ανάγωση [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Επιστρέφει τη λειτουργία γεμίσματος εικόνας. Ανάγνωση [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Επιστρέφει το κάτω άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το κάτω άκρο του περιγραμμένου του σχήματος. Θέση θετικού ποσοστού ορίζει εσωτερική μετατόπιση, ενώ αρνητικό ποσοστό ορίζει εξωτερική μετατόπιση. Ανάγνωση **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Επιστρέφει το αριστερό άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το αριστερό άκρο του περιγραμμένου του σχήματος. Θέση θετικού ποσοστού ορίζει εσωτερική μετατόπιση, ενώ αρνητικό ποσοστό ορίζει εξωτερική μετατόπιση. Ανάγνωση **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Επιστρέφει το δεξιό άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το δεξιό άκρο του περιγραμμένου του σχήματος. Θέση θετικού ποσοστού ορίζει εσωτερική μετατόπιση, ενώ αρνητικό ποσοστό ορίζει εξωτερική μετατόπιση. Ανάγνωση **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Επιστρέφει το πάνω άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το πάνω άκρο του περιγραμμένου του σχήματος. Θέση θετικού ποσοστού ορίζει εσωτερική μετατόπιση, ενώ αρνητικό ποσοστό ορίζει εξωτερική μετατόπιση. Ανάγνωση **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Επιστρέφει τον τρόπο ευθυγράμμισης της υφής μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου υφής και πώς επαναλαμβάνεται στο σχήμα. Ανάγνωση [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κάθετο ή και τους δύο άξονες. Ανάγνωση [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Επιστρέφει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Θετική τιμή μετακινεί την υφή προς τα δεξιά, αρνητική τιμή προς τα αριστερά. Ανάγνωση **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Επιστρέφει την κάθετη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Θετική τιμή μετακινεί την υφή προς τα κάτω, αρνητική τιμή προς τα πάνω. Ανάγνωση **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Επιστρέφει την οριζόντια κλίμαка της γεμίσματος υφής ως ποσοστό. Ανάγνωση **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Επιστρέφει την κάθετη κλίμακα της γεμίσματος υφής ως ποσοστό. Ανάγνωση **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει τον κωδικό hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Κλήση απευθείας ή χρήση του αντικειμένου φρουράς [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής των υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με αναφορά προς nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Ορίζει τον αριθμό των ποσοστών του πραγματικού ύψους εικόνας που περικόπτεται από το κάτω μέρος της εικόνας. Εγγραφή **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Ορίζει τον αριθμό των ποσοστών του πραγματικού πλάτους εικόνας που περικόπτεται από το αριστερό μέρος της εικόνας. Εγγραφή **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Ορίζει τον αριθμό των ποσοστών του πραγματικού πλάτους εικόνας που περικόπτεται από το δεξιό μέρος της εικόνας. Εγγραφή **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Ορίζει τον αριθμό των ποσοστών του πραγματικού ύψους εικόνας που περικόπτεται από το πάνω μέρος της εικόνας. Εγγραφή **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Ορίζει τα dpi που χρησιμοποιούνται για τη γεμίσματος μιας εικόνας. Εγγραφή **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Ορίζει τη λειτουργία γεμίσματος εικόνας. Εγγραφή [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Ορίζει το κάτω άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το κάτω άκρο του περιγράμματος του σχήματος. Θετικό ποσοστό ορίζει εσωτερική μετατόπιση, αρνητικό ποσοστό εξωτερική. Εγγραφή **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Ορίζει το αριστερό άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το αριστερό άκρο του περιγράμματος του σχήματος. Θετικό ποσοστό ορίζει εσωτερική μετατόπιση, αρνητικό ποσοστό εξωτερική. Εγγραφή **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Ορίζει το δεξιό άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το δεξιό άκρο του περιγράμματος του σχήματος. Θετικό ποσοστό ορίζει εσωτερική μετατόπιση, αρνητικό ποσοστό εξωτερική. Εγγραφή **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Ορίζει το πάνω άκρο του παραλληλογράμμου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από το πάνω άκρο του περιγράμματος του σχήματος. Θετικό ποσοστό ορίζει εσωτερική μετατόπιση, αρνητικό ποσοστό εξωτερική. Εγγραφή **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Ορίζει τον τρόπο ευθυγράμμισης της υφής μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου υφής και πώς επαναλαμβάνεται στο σχήμα. Εγγραφή [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κάθετο ή και τους δύο άξονες. Εγγραφή [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Ορίζει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Θετική τιμή μετακινεί την υφή προς τα δεξιά, αρνητική τιμή προς τα αριστερά. Εγγραφή **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Ορίζει την κάθετη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Θετική τιμή μετακινεί την υφή προς τα κάτω, αρνητική τιμή προς τα πάνω. Εγγραφή **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Ορίζει την οριζόντια κλίμακα της γεμίσματος υφής ως ποσοστό. Εγγραφή **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Ορίζει την κάθετη κλίμακα της γεμίσματος υφής ως ποσοστό. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκεύασμα C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση απευθείας ή χρήση του αντικειμένου φρουράς [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IPictureFillFormat](../ipicturefillformat/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)