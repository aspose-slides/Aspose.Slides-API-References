---
title: XmlConvert
second_title: Aspose.Slides για C++ API Αναφορά
description: Κωδικοποιεί και αποκωδικοποιεί ονόματα XML, και παρέχει μεθόδους για μετατροπή μεταξύ τύπων χρόνου εκτέλεσης και τύπων γλώσσας ορισμού σχήματος XML (XSD). Κατά τη μετατροπή τύπων δεδομένων, οι επιστρεφόμενες τιμές είναι ανεξάρτητες από την τοπική ρύθμιση.
type: docs
weight: 157
url: /el/system.xml/xmlconvert/
---
## XmlConvert κλάση

Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Αποκωδικοποιεί ένα όνομα. Αυτή η μέθοδος κάνει το αντίστροφο των μεθόδων XmlConvert::EncodeName(String) και XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Μετατρέπει το όνομα σε έγκυρο τοπικό όνομα XML. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Μετατρέπει το όνομα σε έγκυρο όνομα XML. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Επαληθεύει ότι το όνομα είναι έγκυρο σύμφωνα με την προδιαγραφή XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Ελέγχει αν ο δοθείς χαρακτήρας είναι έγκυρος τύπος χαρακτήρα χωρίς άνω κάτω τελεία. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Επιστρέφει το δοθέν χαρακτήρα αν ο χαρακτήρας στο όρισμα είναι έγκυρος χαρακτήρας δημόσιου id, διαφορετικά **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Ελέγχει αν ο δοθείς χαρακτήρας είναι έγκυρος τύπος Ξεκινήματος Ονόματος. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Ελέγχει αν ο δοθείς χαρακτήρας είναι έγκυρος χαρακτήρας λευκού διαστήματος XML. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Ελέγχει αν ο δοθείς χαρακτήρας είναι έγκυρος χαρακτήρας XML. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Ελέγχει αν το δοθέν ζεύγος αντιπροσωπευτικών χαρακτήρων είναι έγκυρος χαρακτήρας XML. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τέλεση ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινής αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινής αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Μετατρέπει το [String](../../system/string/) σε [DateTime](../../system/datetime/) χρησιμοποιώντας το καθορισμένο XmlDateTimeSerializationMode. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Μετατρέπει το παρεχόμενο [String](../../system/string/) σε ισοδύναμο [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Μετατρέπει το παρεχόμενο [String](../../system/string/) σε ισοδύναμο [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Μετατρέπει το παρεχόμενο [String](../../system/string/) σε ισοδύναμο [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Μετατρέπει το [Boolean](../../system/boolean/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Μετατρέπει το [Char](../../system/char/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Μετατρέπει το [Decimal](../../system/decimal/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Μετατρέπει το [SByte](../../system/sbyte/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Μετατρέπει το [Int16](../../system/int16/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Μετατρέπει το [Int32](../../system/int32/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Μετατρέπει το [Int64](../../system/int64/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Μετατρέπει το [Byte](../../system/byte/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Μετατρέπει το [UInt16](../../system/uint16/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Μετατρέπει το [UInt32](../../system/uint32/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Μετατρέπει το [UInt64](../../system/uint64/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Μετατρέπει το [Single](../../system/single/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Μετατρέπει το [Double](../../system/double/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Μετατρέπει το [TimeSpan](../../system/timespan/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Μετατρέπει το [DateTime](../../system/datetime/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Μετατρέπει το [DateTime](../../system/datetime/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Μετατρέπει το [DateTime](../../system/datetime/) σε [String](../../system/string/) χρησιμοποιώντας το καθορισμένο XmlDateTimeSerializationMode. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Μετατρέπει το παρεχόμενο [DateTimeOffset](../../system/datetimeoffset/) σε [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Μετατρέπει το παρεχόμενο [DateTimeOffset](../../system/datetimeoffset/) σε [String](../../system/string/) στην καθορισμένη μορφή. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Μετατρέπει το [Guid](../../system/guid/) σε [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Μετατρέπει το [String](../../system/string/) σε ισοδύναμο [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Επαληθεύει ότι το όνομα είναι έγκυρο σύμφωνα με τη σύσταση W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Επαληθεύει ότι το όνομα είναι έγκυρο **NCName** σύμφωνα με τη σύσταση W3C Extended Markup Language. Ένα **NCName** είναι ένα όνομα που δεν μπορεί να περιέχει άνω κάτω τελεία. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Επαληθεύει ότι η συμβολοσειρά είναι έγκυρο NMTOKEN σύμφωνα με τη σύσταση W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Επιστρέφει το δοθέν αντικείμενο συμβολοσειράς αν όλοι οι χαρακτήρες στο όρισμα συμβολοσειράς είναι έγκυροι χαρακτήρες δημόσιου id. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Επαληθεύει ότι η συμβολοσειρά είναι έγκυρο token σύμφωνα με τη σύσταση W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Επιστρέφει το δοθέν αντικείμενο αν όλοι οι χαρακτήρες στο όρισμα συμβολοσειράς είναι έγκυροι χαρακτήρες λευκού διαστήματος. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Επιστρέφει τη δοθείσα συμβολοσειρά αν όλοι οι χαρακτήρες και τα ζεύγη surrogate στην συμβολοσειρά είναι έγκυροι χαρακτήρες XML, διαφορετικά γίνεται έξωση XmlException με πληροφορίες για τον πρώτο μη έγκυρο χαρακτήρα που εντοπίστηκε. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι

| Τύπος | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη (shared pointer) σε ένα στιγμιότυπο αυτής της κλάσης. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)