---
title: Metafile
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει ένα γραφικό μετααρχείο. Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 144
url: /el/system.drawing.imaging/metafile/
---
## Metafile κλάση

Represents a graphic metafile. Objects of this κλάση should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this κλάση into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Metafile : public System::Drawing::Image
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [Clone](./clone/)() override | Επιστρέφει ένα αντίγραφο του τρέχοντος αντικειμένου. |
| void [Dispose](../../system.drawing/image/dispose/)() override | Απελευθερώνει όλους τους πόρους που αποκτήθηκαν από το τρέχον αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromFile](../../system.drawing/image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Δημιουργεί ένα αντικείμενο [Image](../../system.drawing/image/) από το καθορισμένο αρχείο. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../../system.drawing/bitmap/)\> [FromHbitmap](../../system.drawing/image/fromhbitmap/)(IntPtr) | Δημιουργεί ένα αντικείμενο [Bitmap](../../system.drawing/bitmap/) από το καθορισμένο bitmap GDI. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromStream](../../system.drawing/image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Δημιουργεί ένα αντικείμενο [Image](../../system.drawing/image/) από τη καθορισμένη ροή. |
| virtual **int32_t** [get_Flags](../../system.drawing/image/get_flags/)() const | Επιστρέφει έναν συνδυασμό σε επίπεδο bit των τιμών του enum ImageFlags που αντιπροσωπεύει τα χαρακτηριστικά της εικόνας. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../../system.drawing/image/get_framedimensionslist/)() const | Επιστρέφει έναν πίνακα GUID που αντιπροσωπεύει τις διαστάσεις των πλαισίων μέσα στην εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| int [get_Height](./get_height/)() const override | Επιστρέφει τα ύψη της εικόνας σε εικονοστοιχεία. |
| **float** [get_HorizontalResolution](../../system.drawing/image/get_horizontalresolution/)() const | Επιστρέφει την οριζόντια ανάλυση της εικόνας που αντιπροσωπεύεται από το τρέχον αντικείμενο σε εικονοστοιχεία ανά ίντσα. |
| virtual [Imaging::ColorPalettePtr](../colorpaletteptr/) [get_Palette](../../system.drawing/image/get_palette/)() const | Επιστρέφει την παλέτα χρωμάτων που χρησιμοποιείται από την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [Imaging::PixelFormat](../pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Επιστρέφει μια τιμή που υποδεικνύει τη μορφή εικονοστοιχείου. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../../system.drawing/image/get_propertyidlist/)() const | Παίρνει τα IDs των στοιχείων ιδιοτήτων που αποθηκεύονται σε αυτήν την εικόνα. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../propertyitem/)\>\> [get_PropertyItems](../../system.drawing/image/get_propertyitems/)() const | Παίρνει όλα τα στοιχεία ιδιοτήτων (κομμάτια μεταδεδομένων) που αποθηκεύονται σε αυτήν την εικόνα. |
| [Imaging::ImageFormatPtr](../imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Επιστρέφει μια τιμή που υποδεικνύει τη μορφή της εικόνας. |
| [Size](../../system.drawing/size/) [get_Size](../../system.drawing/image/get_size/)() const | Επιστρέφει ένα αντικείμενο [Size](../../system.drawing/size/) που αντιπροσωπεύει το πλάτος και το ύψος της εικόνας σε εικονοστοιχεία. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../../system.drawing/image/get_tag/)() const | Παίρνει ένα αντικείμενο που παρέχει πρόσθετα δεδομένα σχετικά με την εικόνα. |
| **float** [get_VerticalResolution](../../system.drawing/image/get_verticalresolution/)() const | Επιστρέφει την κάθετη ανάλυση της εικόνας που αντιπροσωπεύεται από το τρέχον αντικείμενο σε εικονοστοιχεία ανά ίντσα. |
| int [get_Width](./get_width/)() const override | Επιστρέφει το πλάτος της εικόνας σε εικονοστοιχεία. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](../../system.drawing/image/getbounds/)([GraphicsUnit](../../system.drawing/graphicsunit/)\&) | Επιστρέφει τα όρια της εικόνας στις καθορισμένες μονάδες μέτρησης. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| int [GetFrameCount](../../system.drawing/image/getframecount/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&) | Επιστρέφει τον αριθμό των πλαισίων της καθορισμένης διάστασης πλαισίου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος του C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| IntPtr [GetHenhmetafile](./gethenhmetafile/)() | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
| [SharedPtr](../../system/sharedptr/)\<[MetafileHeader](../metafileheader/)\> [GetMetafileHeader](./getmetafileheader/)() | Επιστρέφει μια κεφαλίδα που σχετίζεται με το τρέχον αντικείμενο. |
| static int [GetPixelFormatSize](../../system.drawing/image/getpixelformatsize/)([Imaging::PixelFormat](../pixelformat/)) | Επιστρέφει τον αριθμό των bit που χρησιμοποιούνται για την αναπαράσταση του βάθους χρώματος στη καθορισμένη μορφή εικονοστοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [GetThumbnailImage](../../system.drawing/image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../../system.drawing/image/getthumbnailimageabort/), IntPtr) | Παίρνει μια μικρογραφία για αυτό το αντικείμενο [System::Drawing::Image](../../system.drawing/image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση του C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογική του τελεστή 'is' του C#. |
| static **bool** [IsAlphaPixelFormat](../../system.drawing/image/isalphapixelformat/)([Imaging::PixelFormat](../pixelformat/)) | Καθορίζει αν η καθορισμένη μορφή εικονοστοιχείου περιέχει πληροφορίες άλφα. |
| virtual **bool** [IsMultiImage](../../system.drawing/image/ismultiimage/)() const | Επιστρέφει αν η αρχική μορφή είναι πολλαπλή εικόνα. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Metafile](./metafile/)(const [System::String](../../system/string/)\&) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [EmfType](../emftype/)) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [Rectangle](../../system.drawing/rectangle/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [RectangleF](../../system.drawing/rectanglef/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Metafile](./metafile/)(IntPtr, [EmfType](../emftype/)) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγράφου. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων των υποκατηγοριών. |
| void [PlayRecord](./playrecord/)([EmfPlusRecordType](../emfplusrecordtype/), **int32_t**, **int32_t**, [System::ByteArrayPtr](../../system/bytearrayptr/)) | ΔΕΝ ΕΙΝΑΙ ΥΛΟΠΟΙΗΜΕΝΟ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά το αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [RotateFlip](../../system.drawing/image/rotateflip/)([RotateFlipType](../../system.drawing/rotatefliptype/)) | Περιστρέφει την εικόνα σε πολλαπλάσια του 90 μοιρών και την αναστροφή. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο στο καθορισμένο αρχείο σε μορφή PNG. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο στο καθορισμένο αρχείο στην καθορισμένη μορφή. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο στη καθορισμένη ροή στην καθορισμένη μορφή. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο στο καθορισμένο αρχείο χρησιμοποιώντας τον καθορισμένο κωδικοποιητή και τις παραμέτρους κωδικοποιητή. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο στη καθορισμένη ροή χρησιμοποιώντας τον καθορισμένο κωδικοποιητή και τις παραμέτρους κωδικοποιητή. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Προσθέτει ένα πλαίσιο στο αρχείο ή στη ροή που καθορίστηκε σε προηγούμενη κλήση της μεθόδου [Save()](../../system.drawing/image/save/). |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\>\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Προσθέτει ένα πλαίσιο στο αρχείο ή στη ροή που καθορίστηκε σε προηγούμενη κλήση της μεθόδου [Save()](../../system.drawing/image/save/). |
| int [SelectActiveFrame](../../system.drawing/image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&, int) | Επιλέγει το καθορισμένο πλαίσιο. |
| virtual void [set_Palette](../../system.drawing/image/set_palette/)([Imaging::ColorPalettePtr](../colorpaletteptr/)) | Ορίζει την παλέτα χρωμάτων που χρησιμοποιείται από την εικόνα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual void [set_Tag](../../system.drawing/image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ορίζει ένα αντικείμενο που παρέχει πρόσθετα δεδομένα σχετικά με την εικόνα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοκάρια σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Metafile](./~metafile/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Image](../../system.drawing/image/)
* Χώρος ονομάτων [System::Drawing::Imaging](../)
* Βιβλιοθήκη [Aspose.Slides](../../)