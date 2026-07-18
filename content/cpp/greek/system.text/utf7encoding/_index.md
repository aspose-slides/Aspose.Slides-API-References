---
title: UTF7Encoding
second_title: Aspose.Slides για C++ - Αναφορά API
description: "Κωδικοποίηση UTF-7. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 365
url: /el/system.text/utf7encoding/
---
## UTF7Encoding κλάση

Κωδικοποίηση UTF-7. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο με τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Κλωνοποιεί το αντικείμενο κωδικοποίησης. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Μετατρέπει τα bytes μεταξύ δύο κωδικοποιήσεων. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Μετατρέπει τα bytes μεταξύ δύο κωδικοποιήσεων. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει με το αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση τύπου float C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση τύπου double C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Λαμβάνει την κωδικοποίηση ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης Unicode big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης UTF-32 big-endian. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με το σώμα του πράκτορα αλληλογραφίας. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Λαμβάνει το ID κωδικοσελίδας [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Λαμβάνει το fallback αποκωδικοποιητή. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Λαμβάνει την προεπιλεγμένη κωδικοποίηση. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Λαμβάνει το fallback κωδικοποιητή. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Λαμβάνει το όνομα κωδικοποίησης σε ανθρώπινη μορφή. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με την κεφαλίδα του πράκτορα αλληλογραφίας. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε περιηγητή για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε περιηγητή για την αποθήκευση περιεχομένου. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε πρόγραμμα αλληλογραφίας για την εμφάνιση περιεχομένου. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ελέγχει αν η κωδικοποίηση μπορεί να χρησιμοποιηθεί σε πρόγραμμα αλληλογραφίας για την αποθήκευση περιεχομένου. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ελέγχει αν η κωδικοποίηση είναι μόνο για ανάγνωση. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Ελέγχει αν η κωδικοποίηση είναι μονό-μπάιτ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Λαμβάνει την κωδικοποίηση Latin1. ΜΟΝΟ ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Λαμβάνει το τυπικό αντικείμενο κωδικοποίησης UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Μόνο εσωτερική, για χρήση από τις βιβλιοθήκες κλάσεων: χωρίς σήμανση και χωρίς επικύρωση εισόδου. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Λαμβάνει το όνομα κωδικοποίησης συμβατό με IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Λαμβάνει το ID κωδικοσελίδας [Windows](../../system.windows/). |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση μιας συμβολοσειράς. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Λαμβάνει τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer bytes. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer bytes. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer bytes. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer bytes. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Λαμβάνει έναν αποκωδικοποιητή που προωθεί τα αιτήματα σε αυτό το αντικείμενο. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Λαμβάνει έναν κωδικοποιητή που προωθεί τα αιτήματα σε αυτό το αντικείμενο. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Λαμβάνει κωδικοποίηση βάσει ονόματος. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Λαμβάνει κωδικοποίηση βάσει κωδικοσελίδας. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Λαμβάνει κωδικοποίηση βάσει κωδικοσελίδας. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Λαμβάνει κωδικοποίηση βάσει ονόματος. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Λαμβάνει τη λίστα των γνωστών κωδικοποιήσεων. |
| int [GetHashCode](./gethashcode/)() const override | Λαμβάνει το hash code της κωδικοποίησης. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Λαμβάνει τον μέγιστο αριθμό bytes που απαιτούνται για την κωδικοποίηση ενός καθορισμένου αριθμού χαρακτήρων. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Λαμβάνει τον μέγιστο αριθμό χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός καθορισμένου αριθμού bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Επιστρέφει μια ακολουθία bytes που υποδεικνύει την κωδικοποίηση (π.χ. BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Αποκωδικοποιεί ένα buffer bytes σε μια συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγράφου. Στην πραγματικότητα δεν αντιγράφει τίποτα, μόνο αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, μόνο αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Συγκρίνει τις παραμέτρους κωδικοποιήσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ορίζει το fallback αποκωδικοποιητή. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ορίζει το fallback κωδικοποιητή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
|  [UTF7Encoding](./utf7encoding/)() | Κατασκευαστής. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | Κατασκευαστής. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Προεπιλεγμένη τιμή κωδικοσελίδας. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Μαγικός αριθμός που χρησιμοποιείται από το [Windows](../../system.windows/) για το ID κωδικοσελίδας UTF-7. |

## Δείτε επίσης

* Κλάση [Encoding](../encoding/)
* Χώρος ονομάτων [System::Text](../)
* Βιβλιοθήκη [Aspose.Slides](../../)