---
title: Rijndael
second_title: Aspose.Slides για C++ Αναφορά API
description: "Βασική κλάση για τον αλγόριθμο Rijndael. Τα αντικείμενα αυτής της κλάσης θα πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε αντίτυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα περιβλείψτε αυτήν την κλάση σε System::SmartPtr pointer και χρησιμοποιήστε αυτόν τον pointer για να τον περάσετε στις functions ως argument."
type: docs
weight: 404
url: /el/system.security.cryptography/rijndael/
---
## Rijndael κλάση

Βασική κλάση για [Rijndael](./) αλγόριθμο. Τα αντικείμενα αυτής της κλάσης θα πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας [System::MakeObject()](../../system/makeobject/) function. Ποτέ μην δημιουργήσετε αντίτυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε [System::SmartPtr](../../system/smartptr/) pointer και χρησιμοποιήστε αυτό το pointer για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class Rijndael : public System::Security::Cryptography::SymmetricAlgorithm
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Δημιουργεί μια παρουσία αλγορίθμου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)() | Δημιουργεί αποκρυπτοποιητή με παραμέτρους που σχετίζονται με το αντικείμενο αλγορίθμου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Δημιουργεί αποκρυπτοποιητή με ρητές παραμέτρους. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)() | Δημιουργεί κρυπτοποιητή με παραμέτρους που σχετίζονται με το αντικείμενο αλγορίθμου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Δημιουργεί κρυπτοποιητή με ρητές παραμέτρους. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικές χρήσεις. |
| virtual void [GenerateIV](../symmetricalgorithm/generateiv/)() | Δημιουργεί τυχαία αρχική τιμή για τον αλγόριθμο. Αντικαθιστά την υπάρχουσα (αν υπάρχει). |
| virtual void [GenerateKey](../symmetricalgorithm/generatekey/)() | Δημιουργεί τυχαίο κλειδί για τον αλγόριθμο. Αντικαθιστά το υπάρχον (αν υπάρχει). |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | Λαμβάνει το μέγεθος του μπλοκ της κρυπτογραφικής λειτουργίας. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | Λαμβάνει το μέγεθος ανάδρασης της κρυπτογραφικής λειτουργίας. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | Λαμβάνει την αρχική τιμή της κρυπτογραφικής λειτουργίας. Δημιουργεί νέο αν δεν έχει δημιουργηθεί ακόμη. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | Λαμβάνει το κλειδί της κρυπτογραφικής λειτουργίας. Δημιουργεί νέο αν δεν έχει δημιουργηθεί ακόμη. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | Λαμβάνει το μέγεθος του κλειδιού της κρυπτογραφικής λειτουργίας. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | Λαμβάνει τη λειτουργία της κρυπτογραφικής λειτουργίας. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | Λαμβάνει το γέμισμα της κρυπτογραφικής λειτουργίας. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Δίνει τη δυνατότητα κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση lock() της C# για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστές ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Ορίζει το μέγεθος του μπλοκ της κρυπτογραφικής λειτουργίας. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Ορίζει το μέγεθος ανάδρασης της κρυπτογραφικής λειτουργίας. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ορίζει την αρχική τιμή της κρυπτογραφικής λειτουργίας. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ορίζει το κλειδί της κρυπτογραφικής λειτουργίας. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Ορίζει το μέγεθος του κλειδιού της κρυπτογραφικής λειτουργίας. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Ορίζει τη λειτουργία της κρυπτογραφικής λειτουργίας. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Ορίζει το γέμισμα της κρυπτογραφικής λειτουργίας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως ασθενή δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε ασθενή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση lock() της C# για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Ελέγχει αν το μέγεθος κλειδιού είναι έγκυρο. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το μετρητή ασθενών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το μετρητή ασθενών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [SymmetricAlgorithm](../symmetricalgorithm/)
* Χώρος ονομάτων [System::Security::Cryptography](../)
* Βιβλιοθήκη [Aspose.Slides](../../)