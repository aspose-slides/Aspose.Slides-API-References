---
title: Bitmap
second_title: Αναφορά API Aspose.Slides για C++
description: "Αντιπροσωπεί μια bitmap εικόνα GDI+. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε ένα αντίτυπο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα εξακρίβωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr pointer και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως argument."
type: docs
weight: 1
url: /el/system.drawing/bitmap/
---
## Κλάση Bitmap

Αναπαριστά μια bitmap εικόνα GDI+. Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε αντίστοιχο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα εξακρίβωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class Bitmap : public System::Drawing::Image
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Ενεργοποιεί τη λειτουργία επεξεργασίας εικονοστοιχείων. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο από την καθορισμένη υπάρχουσα εικόνα. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο από το καθορισμένο ρεύμα. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο από το καθορισμένο αρχείο. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο από το καθορισμένο αρχείο. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο που αντιπροσωπεύει μια bitmap εικόνα με το καθορισμένο πλάτος, ύψος, μορφή εικονοστοιχείων και δεδομένα εικονοστοιχείων. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο από την καθορισμένη υπάρχουσα εικόνα, κλιμακωμένο στο καθορισμένο μέγεθος. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Δημιουργεί ένα νέο [Bitmap](./) αντικείμενο από την καθορισμένη υπάρχουσα εικόνα με πλάτος και ύψος κλιμακωμένα στις καθορισμένες τιμές. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Δημιουργεί ένα [Bitmap](./) αντικείμενο που αντιπροσωπεύει ένα αντίγραφο ενός τμήματος της bitmap εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Δημιουργεί ένα [Bitmap](./) αντικείμενο που αντιπροσωπεύει ένα αντίγραφο ενός τμήματος της bitmap εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Υπολογίζει την τιμή κατατεμαχισμού SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Δημιουργεί ένα αντίγραφο της καθορισμένης bitmap εικόνας με μορφή εικονοστοιχείων αλλαγμένη σε Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Απελευθερώνει όλους τους πόρους που απέκτησε το τρέχον αντικείμενο. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Απενεργοποιεί τη λειτουργία επεξεργασίας εικονοστοιχείων. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Δημιουργεί ένα [Image](../image/) αντικείμενο από το καθορισμένο αρχείο. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Δημιουργεί ένα [Bitmap](./) αντικείμενο από το καθορισμένο bitmap GDI. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Δημιουργεί ένα [Image](../image/) αντικείμενο από το καθορισμένο ρεύμα. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Επιστρέφει έναν συνδυασμό bitwise των τιμών του enum ImageFlags που αντιπροσωπεύει τα χαρακτηριστικά της εικόνας. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Επιστρέφει έναν πίνακα GUID που αντιπροσωπεύουν τις διαστάσεις των πλαισίων μέσα στην εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο. |
| int [get_Height](./get_height/)() const override | Επιστρέφει το ύψος της εικόνας σε εικονοστοιχεία. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Επιστρέφει την οριζόντια ανάλυση της εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο σε εικονοστοιχεία ανά ίντσα. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Επιστρέφει την παλέτα χρωμάτων που χρησιμοποιεί η εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Επιστρέφει τη μορφή εικονοστοιχείων της εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Λαμβάνει τα IDs των στοιχείων ιδιοτήτων που αποθηκεύονται σε αυτήν την εικόνα. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Λαμβάνει όλα τα στοιχεία ιδιοτήτων (μερίδια μεταδεδομένων) που αποθηκεύονται σε αυτήν την εικόνα. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Επιστρέφει τη μορφή αρχείου της εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Επιστρέφει ένα [Size](../size/) αντικείμενο που αντιπροσωπεύει το πλάτος και το ύψος της εικόνας σε εικονοστοιχεία. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Λαμβάνει ένα αντικείμενο που παρέχει πρόσθετα δεδομένα σχετικά με την εικόνα. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Επιστρέφει την κατακόρυφη ανάλυση της εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο σε εικονοστοιχεία ανά ίντσα. |
| int [get_Width](./get_width/)() const override | Επιστρέφει το πλάτος της εικόνας σε εικονοστοιχεία. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Επιστρέφει τα όρια της εικόνας στις καθορισμένες μονάδες μέτρησης. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Επιστρέφει τον αριθμό πλαισίων της καθορισμένης διάστασης πλαισίου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το κατατεματισμό προσαρμοσμένων αντικειμένων. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Δημιουργεί ένα αντικείμενο bitmap GDI από το bitmap που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Επιστρέφει το χρώμα του καθορισμένου εικονοστοιχείου. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Επιστρέφει τον αριθμό των δυαδικών ψηφίων που χρησιμοποιούνται για την αναπαράσταση του βάθους χρώματος στην καθορισμένη μορφή εικονοστοιχείων. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Επιστρέφει έναν ακατέργαστο δείκτη στο υποκείμενο αντικείμενο SkBitmap. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Λαμβάνει μια μικρογραφία για αυτό το [System::Drawing::Image](../image/) αντικείμενο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια实例 του τύπου που περιγράφεται από το targetType. Αναλογία του C# τελεστή 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Καθορίζει αν η καθορισμένη μορφή εικονοστοιχείων περιέχει πληροφορίες άλφα. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Επιστρέφει εάν η αρχική μορφή είναι πολλαπλή εικόνα. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Κλειδώνει ένα [Bitmap](./) στη μνήμη συστήματος. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Κλειδώνει ένα [Bitmap](./) στη μνήμη συστήματος. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Αλλάζει το χρώμα όλων των εικονοστοιχείων με το καθορισμένο χρώμα σε διαφανές. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευάστης αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων σε υποκλάσεις. |
| void [PremultipleColors](./premultiplecolors/)() | Προπληθύνει τα χρώματα των εικονοστοιχείων της εικόνας που αντιπροσωπεύει το τρέχον αντικείμενο. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Περιστρέφει την εικόνα σε πολλαπλάσια των 90 μοιρών και την αντανακλά. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο σε μορφή PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο στην καθορισμένη μορφή. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο ρεύμα στην καθορισμένη μορφή. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο χρησιμοποιώντας τον καθορισμένο κωδικοποιητή και τις παραμέτρους κωδικοποιητή. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο ρεύμα χρησιμοποιώντας τον καθορισμένο κωδικοποιητή και τις παραμέτρους κωδικοποιητή. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Προσθέτει ένα πλαίσιο στο αρχείο ή ρεύμα που καθορίστηκε σε μια προηγούμενη κλήση της μεθόδου [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Προσθέτει ένα πλαίσιο στο αρχείο ή ρεύμα που καθορίστηκε σε μια προηγούμενη κλήση της μεθόδου [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Επιλέγει το καθορισμένο πλαίσιο. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Ορίζει την παλέτα χρωμάτων που χρησιμοποιεί η εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ορίζει ένα αντικείμενο που παρέχει πρόσθετα δεδομένα σχετικά με την εικόνα. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Ορίζει το χρώμα του καθορισμένου εικονοστοιχείου στην bitmap εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Ορίζει την ανάλυση της εικόνας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει την n-στή παράμετρο προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή των δεικτών σε δοχεία σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Ξεκλειδώνει το καθορισμένο bitmap από τη μνήμη συστήματος. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Image](../image/)
* Χώρος ονομάτων [System::Drawing](../)
* Βιβλιοθήκη [Aspose.Slides](../../)