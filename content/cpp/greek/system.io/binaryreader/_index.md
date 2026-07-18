---
title: BinaryReader
second_title: Αναφορά API Aspose.Slides για C++
description: "Αντιπροσωπεύει ένα αναγνώστη που διαβάζει πρωτόγονους τύπους δεδομένων ως δυαδικά δεδομένα σε συγκεκριμένη κωδικοποίηση. Αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 92
url: /el/system.io/binaryreader/
---
## BinaryReader κλάση


Αναπαριστά έναν αναγνώστη που διαβάζει πρωτόγονους τύπους δεδομένων ως δυαδικά δεδομένα σε συγκεκριμένη κωδικοποίηση. Αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα.

```cpp
class BinaryReader : public System::IDisposable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Δημιουργεί μια παρουσία της κλάσης [BinaryReader](./) που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας κωδικοποίηση UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Δημιουργεί μια παρουσία της κλάσης [BinaryReader](./) που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Δημιουργεί μια παρουσία της κλάσης [BinaryReader](./) που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |
| virtual void [Close](./close/)() | Κλείνει το τρέχον αντικείμενο [BinaryReader](./) και τη βασική ροή εισόδου. |
| void [Dispose](./dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από το τρέχον αντικείμενο και κλείνει τη σχετική ροή. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σήμανση C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Επιστρέφει τη ροή εισόδου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμένη αντιστοίχηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάσεων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάσεων μέσω αντιγραφής. |
| virtual int [PeekChar](./peekchar/)() | Διαβάζει έναν χαρακτήρα από τη ροή εισόδου χωρίς να αλλάξει τον δρομέα ανάγνωσης της ροής. |
| virtual int [Read](./read/)() | Διαβάζει έναν χαρακτήρα από τη ροή εισόδου. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Διαβάζει τον καθορισμένο αριθμό byte από τη ροή εισόδου και τα γράφει στον καθορισμένο πίνακα byte. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Διαβάζει τον καθορισμένο αριθμό χαρακτήρων από τη ροή εισόδου, τους μετατρέπει σε κωδικοποίηση UTF-16 και γράφει τους προκύπτοντες χαρακτήρες UTF-16 στον καθορισμένο πίνακα χαρακτήρων ξεκινώντας από τη συγκεκριμένη θέση. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Διαβάζει ένα byte από τη ροή εισόδου και επιστρέφει την λογική του αναπαράσταση. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Διαβάζει ένα byte από τη ροή εισόδου. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Διαβάζει τον καθορισμένο αριθμό byte από τη ροή εισόδου. |
| virtual char_t [ReadChar](./readchar/)() | Διαβάζει έναν χαρακτήρα από τη ροή εισόδου. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Διαβάζει τον καθορισμένο αριθμό χαρακτήρων από τη ροή εισόδου και τους επιστρέφει σε κωδικοποίηση UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | ΔΕΝ ΕΦΑΡΜΟΣΤΕΙ. |
| virtual **double** [ReadDouble](./readdouble/)() | Διαβάζει 8 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Διαβάζει 2 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή ακέραιου 16-bit. |
| virtual int [ReadInt32](./readint32/)() | Διαβάζει 4 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή ακέραιου 32-bit. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Διαβάζει 8 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή ακέραιου 64-bit. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Διαβάζει ένα byte από τη ροή εισόδου και το επιστρέφει ως τιμή υπογεγραμμένου ακέραιου 8-bit. |
| virtual **float** [ReadSingle](./readsingle/)() | Διαβάζει 4 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή κινητής υποδιαστολής μονής ακρίβειας. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Διαβάζει μια συμβολοσειρά από την τρέχουσα ροή. Η συμβολοσειρά προεξέχει το μήκος, κωδικοποιημένο ως ακέραιος επτά bits τη φορά. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Διαβάζει 2 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή ακεραίου χωρίς πρόσημο 16-bit. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Διαβάζει 4 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή ακεραίου χωρίς πρόσημο 32-bit. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Διαβάζει 8 byte από τη ροή εισόδου και τα επιστρέφει ως τιμή ακεραίου χωρίς πρόσημο 64-bit. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)