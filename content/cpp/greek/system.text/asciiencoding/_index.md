---
title: ASCIIEncoding
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει την κωδικοποίηση ASCII. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 1
url: /el/system.text/asciiencoding/
---
## ASCIIEncoding κλάση

Αντιπροσωπεύει την κωδικοποίηση ASCII. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | Κατασκευαστής. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | Δημιουργεί αντίγραφο του αντικειμένου κωδικοποίησης. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Μετατρέπει τα byte μεταξύ δύο κωδικοποιήσεων. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Μετατρέπει τα byte μεταξύ δύο κωδικοποιήσεων. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει κωδικοποιήσεις. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Λαμβάνει την κωδικοποίηση ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης Unicode μεγάλης σειράς byte (big-endian). |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης UTF-32 μεγάλης σειράς byte. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με το σώμα του πράκτορα αλληλογραφίας. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Λαμβάνει το ID κωδικοσελίδας [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Λαμβάνει την εναλλακτική μέθοδο αποκωδικοποιητή. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Λαμβάνει την προεπιλεγμένη κωδικοποίηση. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Λαμβάνει την εναλλακτική μέθοδο κωδικοποιητή. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Λαμβάνει το όνομα κωδικοποίησης ευανάγνωστο. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με την κεφαλίδα του πράκτορα αλληλογραφίας. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε περιηγητή για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε περιηγητή για την αποθήκευση περιεχομένου. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε πρόγραμμα αλληλογραφίας για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε πρόγραμμα αλληλογραφίας για την αποθήκευση περιεχομένου. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ελέγχει αν η κωδικοποίηση είναι μόνο για ανάγνωση. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Ελέγχει αν η κωδικοποίηση είναι μονο-byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Λαμβάνει την κωδικοποίηση Latin1. ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Μόνο εσωτερική, για χρήση από τις βιβλιοθήκες κλάσεων: Ασημείωτη και μη επικυρωμένη είσοδο. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Λαμβάνει το ID κωδικοσελίδας [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer byte. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer byte. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Λαμβάνει έναν αποκωδικοποιητή που προωθεί τα αιτήματα σε αυτό το αντικείμενο. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Λαμβάνει έναν κωδικοποιητή που προωθεί τα αιτήματα σε αυτό το αντικείμενο. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Λαμβάνει κωδικοποίηση με βάση το όνομα. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Λαμβάνει κωδικοποίηση με βάση την κωδικοσελίδα. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Λαμβάνει κωδικοποίηση με βάση την κωδικοσελίδα. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Λαμβάνει κωδικοποίηση με βάση το όνομα. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Λαμβάνει λίστα των γνωστών κωδικοποιήσεων. |
| int [GetHashCode](../encoding/gethashcode/)() const override | Δημιουργεί κατακερματισμό (hash) της κωδικοποίησης. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Λαμβάνει το μέγιστο αριθμό byte που μπορεί να κρατήσει μια συμβολοσειρά με γνωστό αριθμό χαρακτήρων. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Λαμβάνει τον μέγιστο αριθμό χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός συγκεκριμένου αριθμού byte. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | Επιστρέφει μια ακολουθία byte που υποδεικνύει την κωδικοποίηση (π.χ. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Κατασκευαστής. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή σε υποκατηγορίες. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή σε υποκατηγορίες. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Συγκρίνει κωδικοποιήσεις χρησιμοποιώντας κωδικοσελίδες. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει το αντικείμενο τύπου τιμής με το nullptr με αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ορίζει την εναλλακτική μέθοδο αποκωδικοποιητή. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ορίζει την εναλλακτική μέθοδο κωδικοποιητή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινή). Επιτρέπει την αλλαγή των δεικτών σε δομές σε αδύναμη κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Προεπιλεγμένη τιμή κωδικοσελίδας. |

## Δείτε επίσης

* Κλάση [ICUEncoding](../icuencoding/)
* Χώρος ονομάτων [System::Text](../)
* Βιβλιοθήκη [Aspose.Slides](../../)