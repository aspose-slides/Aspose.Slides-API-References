---
title: Encoding
second_title: Aspose.Slides για C++ API Αναφορά
description: Υπηρεσίες κωδικοποίησης.
type: docs
weight: 222
url: /el/system.text/encoding/
---
## Κλάση Encoding


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Δημιουργεί κλώνο του αντικειμένου κωδικοποίησης. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Μετατρέπει bytes μεταξύ δύο κωδικοποιήσεων. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Μετατρέπει bytes μεταξύ δύο κωδικοποιήσεων. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει κωδικοποιήσεις. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Αποκτά την κωδικοποίηση ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Αποκτά το τυπικό αντικείμενο κωδικοποίησης Unicode big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Αποκτά το τυπικό αντικείμενο κωδικοποίησης UTF-32 big-endian. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Αποκτά το όνομα κωδικοποίησης συμβατό με το σώμα του πράκτορα αλληλογραφίας. |
| virtual int [get_CodePage](./get_codepage/)() | Αποκτά το ID κωδικοσελίδας [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Αποκτά το fallback του αποκωδικοποιητή. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Αποκτά την προεπιλεγμένη κωδικοποίηση. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Αποκτά το fallback του κωδικοποιητή. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Αποκτά το όνομα κωδικοποίησης που είναι κατανοητό από ανθρώπους. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Αποκτά το όνομα κωδικοποίησης συμβατό με την κεφαλίδα του πράκτορα αλληλογραφίας. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί στο πρόγραμμα περιήγησης για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί στο πρόγραμμα περιήγησης για την αποθήκευση περιεχομένου. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί στον πελάτη αλληλογραφίας για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί στον πελάτη αλληλογραφίας για την αποθήκευση περιεχομένου. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Ελέγχει αν η κωδικοποίηση είναι μόνο για ανάγνωση. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Ελέγχει αν η κωδικοποίηση είναι μονό-byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Αποκτά την κωδικοποίηση Latin1. ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Αποκτά το τυπικό αντικείμενο κωδικοποίησης Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Αποκτά το τυπικό αντικείμενο κωδικοποίησης UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Αποκτά το τυπικό αντικείμενο κωδικοποίησης UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Μόνο εσωτερική, για χρήση από τις βιβλιοθήκες κλάσεων: Ασημειωμένη και μη-επικυρωτική εισόδου. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Αποκτά το όνομα κωδικοποίησης συμβατό με IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Αποκτά το ID κωδικοσελίδας [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση μιας συμβολοσειράς. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Παίρνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Παίρνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Παίρνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Παίρνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Παίρνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Παίρνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφορών που συμβάλλει στο αντικείμενο. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Παίρνει έναν αποκωδικοποιητή που προωθεί αιτήματα σε αυτό το αντικείμενο. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Παίρνει έναν κωδικοποιητή που προωθεί αιτήματα σε αυτό το αντικείμενο. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Αποκτά κωδικοποίηση βάσει ονόματος. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Αποκτά κωδικοποίηση βάσει κωδικοσελίδας. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Αποκτά κωδικοποίηση βάσει κωδικοσελίδας. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Αποκτά κωδικοποίηση βάσει ονόματος. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Αποκτά λίστα γνωστών κωδικοποιήσεων. |
| int [GetHashCode](./gethashcode/)() const override | Καταχωρεί hash της κωδικοποίησης. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Παίρνει το μέγιστο αριθμό byte που απαιτούνται για την κωδικοποίηση ενός συγκεκριμένου αριθμού χαρακτήρων. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Παίρνει το μέγιστο αριθμό χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός συγκεκριμένου αριθμού byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Επιστρέφει μια ακολουθία byte που ορίζει την κωδικοποίηση (π.χ. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο του κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση τύπου που περιγράφεται από το targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί το νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί το νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ορίζει το fallback του αποκωδικοποιητή. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ορίζει το fallback του κωδικοποιητή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη σύνταξη typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδία | Περιγραφή |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Προεπιλεγμένη τιμή κωδικοσελίδας. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Δείτε επίσης

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)