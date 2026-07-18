---
title: Latin1Encoding
second_title: Aspose.Slides για C++ API Αναφορά
description: "Υποστήριξη κωδικοποίησης Latin1. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση με δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε ως όρισμα σε συναρτήσεις."
type: docs
weight: 313
url: /el/system.text/latin1encoding/
---
## Latin1Encoding κλάση

Υποστήριξη κωδικοποίησης Latin1. Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκληθούν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση με έναν δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε ως όρισμα σε συναρτήσεις.

```cpp
class Latin1Encoding : public System::Text::ICUEncoding
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | Κλωνοποιεί το αντικείμενο κωδικοποίησης. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Μετατρέπει τα byte μεταξύ δύο κωδικοποιήσεων. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Μετατρέπει τα byte μεταξύ δύο κωδικοποιήσεων. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει κωδικοποιήσεις. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Επιστρέφει την κωδικοποίηση ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Επιστρέφει το αντικείμενο της τυπικής big-endian κωδικοποίησης Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Επιστρέφει το αντικείμενο της τυπικής big-endian κωδικοποίησης UTF-32. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Επιστρέφει το όνομα κωδικοποίησης συμβατό με το σώμα του mail agent. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Λαμβάνει το ID σελίδας κωδικοποίησης [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Λαμβάνει την εναλλακτική αποκωδικοποιητή. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Λαμβάνει την προεπιλεγμένη κωδικοποίηση. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Λαμβάνει την εναλλακτική κωδικοποιητή. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Λαμβάνει το όνομα κωδικοποίησης σε αναγνώσιμη μορφή. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με την κεφαλίδα του mail agent. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε περιηγητή για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε περιηγητή για την αποθήκευση περιεχομένου. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε πρόγραμμα αλληλογραφίας για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε πρόγραμμα αλληλογραφίας για την αποθήκευση περιεχομένου. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ελέγχει αν η κωδικοποίηση είναι μόνο για ανάγνωση. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Έλεγχος αν η κωδικοποίηση είναι μονό byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Λαμβάνει την κωδικοποίηση Latin1. ΜΟΝΟ ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Λαμβάνει το αντικείμενο της τυπικής Unicode κωδικοποίησης. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Λαμβάνει το αντικείμενο της τυπικής κωδικοποίησης UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Λαμβάνει το αντικείμενο της τυπικής κωδικοποίησης UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Μόνο εσωτερική, να χρησιμοποιείται από τις βιβλιοθήκες κλάσεων: Ασημείωτη και μη-επαληθευόμενη εισαγωγή. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με το IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Λαμβάνει το ID σελίδας κωδικοποίησης [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Λαμβάνει έναν αποκωδικοποιητή που προωθεί τα αιτήματα σε αυτό το αντικείμενο. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Λαμβάνει έναν κωδικοποιητή που προωθεί τα αιτήματα σε αυτό το αντικείμενο. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Λαμβάνει κωδικοποίηση βάσει ονόματος. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Λαμβάνει κωδικοποίηση βάσει κωδικοσελίδας. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Λαμβάνει κωδικοποίηση βάσει κωδικοσελίδας. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Λαμβάνει κωδικοποίηση βάσει ονόματος. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Λαμβάνει λίστα των γνωστών κωδικοποιήσεων. |
| int [GetHashCode](../encoding/gethashcode/)() const override | Δημιουργεί κατακερματισμό της κωδικοποίησης. |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | Λαμβάνει το μέγιστο αριθμό bytes που απαιτούνται για την κωδικοποίηση συγκεκριμένου αριθμού χαρακτήρων. |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | Λαμβάνει το μέγιστο αριθμό χαρακτήρων που απαιτούνται για την αποκωδικοποίηση συγκεκριμένου αριθμού bytes. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | Επιστρέφει μια σειρά bytes που υποδεικνύει την κωδικοποίηση (π.χ. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό κάλεσμα C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Κατασκευαστής. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του C# 'is'. |
|  [Latin1Encoding](./latin1encoding/)() | Κατασκευαστής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή κλειδώματος C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγορίων. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Συγκρίνει κωδικοποιήσεις χρησιμοποιώντας κωδικοσελίδες. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ορίζει την εναλλακτική αποκωδικοποιητή. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ορίζει την εναλλακτική κωδικοποιητή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για shared). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή ξεκλειδώματος C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Προεπιλεγμένη τιμή κωδικοσελίδας. |
| static constexpr [LATIN1_CODE_PAGE](./latin1_code_page/) | Κωδικοσελίδα. |

## Δείτε επίσης

* Κλάση [ICUEncoding](../icuencoding/)
* Χώρος ονομάτων [System::Text](../)
* Βιβλιοθήκη [Aspose.Slides](../../)