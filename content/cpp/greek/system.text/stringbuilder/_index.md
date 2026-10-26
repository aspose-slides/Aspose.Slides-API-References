---
title: StringBuilder
second_title: Aspose.Slides για C++ - Αναφορά API
description: "Προσωρινή μνήμη για τη συσσωμάτωση κειμένου τμήμα-τμήμα. Αυτός ο τύπος μπορεί να κατανεμηθεί είτε στη στοίβα ως τύπος τιμής είτε στην σωρού χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Μonce το αντικείμενο κατανεμηθεί, μην αναμειγνύετε αυτές τις δύο περιπτώσεις χρήσης: η ύπαρξη δεικτών SmartPtr σε αντικείμενα που έχουν κατανεμηθεί στη στοίβα απαγορεύεται αυστηρά."
type: docs
weight: 326
url: /el/system.text/stringbuilder/
---
## StringBuilder κλάση


[Buffer](../../system/buffer/) για τη συσσωμάτωση κειμένου τμήμα-τμήμα. Αυτός ο τύπος μπορεί να κατανεμηθεί είτε στη στοίβα ως τύπος αξίας είτε στη σωρού χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Μonce το αντικείμενο κατανεμηθεί, μην αναμείξετε αυτές τις δύο περιπτώσεις χρήσης: η ύπαρξη δεικτών [SmartPtr](../../system/smartptr/) σε αντικείμενα που έχουν κατανεμηθεί στη στοίβα απαγορεύεται αυστηρά.

```cpp
class StringBuilder : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Προσθέτει χαρακτήρα στον builder. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Προσθέτει χαρακτήρες στον builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Προσθέτει πίνακα χαρακτήρων στον builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Προσθέτει τμήμα πίνακα χαρακτήρων στον builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Προσθέτει συμβολοσειρά στον builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Προσθέτει τμήμα συμβολοσειράς στον builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Προσθέτει την αναπαράσταση συμβολοσειράς του αντικειμένου στον builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Προσθέτει το περιεχόμενο του builder στον builder. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Προσθέτει τιμή κινητής υποδιαστολής στον builder. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Προσθέτει τιμή κινητής υποδιαστολής στον builder. |
| [StringBuilder](./) * [Append](./append/)(int) | Προσθέτει ακέραια τιμή στον builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Προσθέτει αριθμητική τιμή στον builder. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Προσθέτει την αναπαράσταση συμβολοσειράς της τιμής enum στον builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Προσαρτώνται μορφοποιημένη συμβολοσειρά στον builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Προσαρτώνται μορφοποιημένη συμβολοσειρά στον builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Προσαρτώνται χαρακτήρα νέας γραμμής στον builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Προσαρτώνται συμβολοσειρά ακολουθούμενη από χαρακτήρα νέας γραμμής στον builder. |
| [StringBuilder](./) * [Clear](./clear/)() | Αφαιρεί όλους τους χαρακτήρες από τον builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Αντιγράφει τα δεδομένα του builder σε υπάρχουσες θέσεις πίνακα. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Εξασφαλίζει ότι η χωρητικότητα αυτής της παρουσίας του [System.Text.StringBuilder](./) είναι τουλάχιστον η καθορισμένη τιμή. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| int [get_Capacity](./get_capacity/)() const | Λαμβάνει την τρέχουσα χωρητικότητα του string builder. |
| int [get_Length](./get_length/)() const | Λαμβάνει το μήκος της συμβολοσειράς που βρίσκεται τώρα στον builder. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την παραγωγή hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Λαμβάνει τον χαρακτήρα στη συγκεκριμένη θέση. |
| void [idx_set](./idx_set/)(int, char_t) | Ορίζει χαρακτήρα στη συγκεκριμένη θέση. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Εισάγει συμβολοσειρά σε σταθερή θέση του builder. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Εισάγει επαναλαμβανόμενη συμβολοσειρά σε σταθερή θέση του builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Εισάγει χαρακτήρα σε σταθερή θέση του builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Εισάγει χαρακτήρες σε σταθερή θέση του builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Εισάγει τιμή σε σταθερή θέση του builder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου όπως περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| char_t [operator[]](./operator[]/)(int) const | Λαμβάνει τον χαρακτήρα στη συγκεκριμένη θέση. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Αφαιρεί τμήμα από τον builder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Αντικαθιστά υποσυμβολοσειρά μέσα από τον builder. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Αντικαθιστά υποσυμβολοσειρά στο εύρος του builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Αντικαθιστά χαρακτήρα μέσα από τον builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Αντικαθιστά χαρακτήρα στο εύρος του builder. |
| void [set_Capacity](./set_capacity/)(int) | Ορίζει τη τρέχουσα χωρητικότητα του string builder. |
| void [set_Length](./set_length/)(int) | Κόβει ή επεκτείνει το string builder στο καθορισμένο μήκος. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινή). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δεικτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δεικτες ή ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Κατασκευαστής. |
|  [StringBuilder](./stringbuilder/)(int) | Κατασκευαστής. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Κατασκευαστής. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Κατασκευαστής. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Λαμβάνει τη συμβολοσειρά που υπάρχει τώρα στον builder. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Λαμβάνει την υποσυμβολοσειρά που υπάρχει τώρα στον builder. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το άνοιγμα του statement lock() της C#. Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δεικτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δεικτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
|  [~StringBuilder](./~stringbuilder/)() | Καταστροφέας. |
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Text](../)
* Βιβλιοθήκη [Aspose.Slides](../../)