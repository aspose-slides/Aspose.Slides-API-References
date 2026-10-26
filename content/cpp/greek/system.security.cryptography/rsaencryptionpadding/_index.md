---
title: RSAEncryptionPadding
second_title: Αναφορά API του Aspose.Slides για C++
description: Λειτουργία γεμίσματος και παράμετροι για λειτουργίες κρυπτογράφησης ή αποκρυπτογράφησης RSA.
type: docs
weight: 482
url: /el/system.security.cryptography/rsaencryptionpadding/
---
## RSAEncryptionPadding κλάση

Λειτουργία γεμίσματος και παράμετροι για [RSA](../rsa/) κρυπτογράφηση ή αποκρυπτογράφηση.

```cpp
class RSAEncryptionPadding : public System::IEquatable<SharedPtr<RSAEncryptionPadding>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [CreateOaep](./createoaep/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | Δημιουργεί [RSAEncryptionPadding](./) με λειτουργία OAEP και καθορισμένο αλγόριθμο κατακερματισμού. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\>) override |  |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Καθορίζει εάν τα τρέχοντα και τα καθορισμένα αντικείμενα είναι ίσα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρά το γεγονός ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρά το γεγονός ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [RSAEncryptionPaddingMode](../rsaencryptionpaddingmode/) [get_Mode](./get_mode/)() const | Λαμβάνει τη λειτουργία γεμίσματος. |
| const [HashAlgorithmName](../hashalgorithmname/)\& [get_OaepHashAlgorithm](./get_oaephashalgorithm/)() const | Λαμβάνει τον αλγόριθμο κατακερματισμού που χρησιμοποιείται με OAEP. |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA1](./get_oaepsha1/)() | Λαμβάνει λειτουργία OAEP με αλγόριθμο κατακερματισμού [SHA1](../sha1/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA256](./get_oaepsha256/)() | Λαμβάνει λειτουργία OAEP με αλγόριθμο κατακερματισμού [SHA256](../sha256/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA384](./get_oaepsha384/)() | Λαμβάνει λειτουργία OAEP με αλγόριθμο κατακερματισμού [SHA384](../sha384/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA512](./get_oaepsha512/)() | Λαμβάνει λειτουργία OAEP με αλγόριθμο κατακερματισμού [SHA512](../sha512/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_Pkcs1](./get_pkcs1/)() | Λαμβάνει λειτουργία PKCS #1 v1.5. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| int [GetHashCode](./gethashcode/)() const override | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα εντολής C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπων ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα εντολής C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IEquatable](../../system/iequatable/)
* Χώρος ονομάτων [System::Security::Cryptography](../)
* Βιβλιοθήκη [Aspose.Slides](../../)