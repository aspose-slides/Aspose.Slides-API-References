---
title: ColorMatrix
second_title: Αναφορά API του Aspose.Slides για C++
description: "Αναπαριστά έναν πίνακα 5x5 που περιέχει τις συντεταγμένες για το χρωματικό χώρο RGBAW. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 27
url: /el/system.drawing.imaging/colormatrix/
---
## ColorMatrix κλάση

Αναπαριστά έναν πίνακα 5x5 που περιέχει τις συντεταγμένες για το χρωματικό χώρο RGBAW. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class ColorMatrix : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Δημιουργεί μια νέα παρουσία της [ColorMatrix](./) κλάση και την αρχικοποιεί με τις τιμές του μοναδιαίου πίνακα. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Δημιουργεί μια νέα παρουσία της [ColorMatrix](./) κλάση και την αρχικοποιεί με τις καθορισμένες τιμές. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_Matrix00](./get_matrix00/)() const | Επιστρέφει μια τιμή στην 0-η γραμμή και 0-η στήλη. |
| **float** [get_Matrix01](./get_matrix01/)() const | Επιστρέφει μια τιμή στην 0-η γραμμή και 1-η στήλη. |
| **float** [get_Matrix02](./get_matrix02/)() const | Επιστρέφει μια τιμή στην 0-η γραμμή και 2-η στήλη. |
| **float** [get_Matrix03](./get_matrix03/)() const | Επιστρέφει μια τιμή στην 0-η γραμμή και 3-η στήλη. |
| **float** [get_Matrix04](./get_matrix04/)() const | Επιστρέφει μια τιμή στην 0-η γραμμή και 4-η στήλη. |
| **float** [get_Matrix10](./get_matrix10/)() const | Επιστρέφει μια τιμή στην 1-η γραμμή και 0-η στήλη. |
| **float** [get_Matrix11](./get_matrix11/)() const | Επιστρέφει μια τιμή στην 1-η γραμμή και 1-η στήλη. |
| **float** [get_Matrix12](./get_matrix12/)() const | Επιστρέφει μια τιμή στην 1-η γραμμή και 2-η στήλη. |
| **float** [get_Matrix13](./get_matrix13/)() const | Επιστρέφει μια τιμή στην 1-η γραμμή και 3-η στήλη. |
| **float** [get_Matrix14](./get_matrix14/)() const | Επιστρέφει μια τιμή στην 1-η γραμμή και 4-η στήλη. |
| **float** [get_Matrix20](./get_matrix20/)() const | Επιστρέφει μια τιμή στην 2-η γραμμή και 0-η στήλη. |
| **float** [get_Matrix21](./get_matrix21/)() const | Επιστρέφει μια τιμή στην 2-η γραμμή και 1-η στήλη. |
| **float** [get_Matrix22](./get_matrix22/)() const | Επιστρέφει μια τιμή στην 2-η γραμμή και 2-η στήλη. |
| **float** [get_Matrix23](./get_matrix23/)() const | Επιστρέφει μια τιμή στην 2-η γραμμή και 3-η στήλη. |
| **float** [get_Matrix24](./get_matrix24/)() const | Επιστρέφει μια τιμή στην 2-η γραμμή και 4-η στήλη. |
| **float** [get_Matrix30](./get_matrix30/)() const | Επιστρέφει μια τιμή στην 3-η γραμμή και 0-η στήλη. |
| **float** [get_Matrix31](./get_matrix31/)() const | Επιστρέφει μια τιμή στην 3-η γραμμή και 1-η στήλη. |
| **float** [get_Matrix32](./get_matrix32/)() const | Επιστρέφει μια τιμή στην 3-η γραμμή και 2-η στήλη. |
| **float** [get_Matrix33](./get_matrix33/)() const | Επιστρέφει μια τιμή στην 3-η γραμμή και 3-η στήλη. |
| **float** [get_Matrix34](./get_matrix34/)() const | Επιστρέφει μια τιμή στην 3-η γραμμή και 4-η στήλη. |
| **float** [get_Matrix40](./get_matrix40/)() const | Επιστρέφει μια τιμή στην 4-η γραμμή και 0-η στήλη. |
| **float** [get_Matrix41](./get_matrix41/)() const | Επιστρέφει μια τιμή στην 4-η γραμμή και 1-η στήλη. |
| **float** [get_Matrix42](./get_matrix42/)() const | Επιστρέφει μια τιμή στην 4-η γραμμή και 2-η στήλη. |
| **float** [get_Matrix43](./get_matrix43/)() const | Επιστρέφει μια τιμή στην 4-η γραμμή και 3-η στήλη. |
| **float** [get_Matrix44](./get_matrix44/)() const | Επιστρέφει μια τιμή στην 4-η γραμμή και 4-η στήλη. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Επιστρέφει μια τιμή στην καθορισμένη γραμμή και στήλη. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Ορίζει τη συγκεκριμένη τιμή στην καθορισμένη θέση του πίνακα. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή C# lock() για κλείδωμα. Κλήστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με αναφορά σε nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Ορίζει μια τιμή στην 0-η γραμμή και 0-η στήλη. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Ορίζει μια τιμή στην 0-η γραμμή και 1-η στήλη. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Ορίζει μια τιμή στην 0-η γραμμή και 2-η στήλη. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Ορίζει μια τιμή στην 0-η γραμμή και 3-η στήλη. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Ορίζει μια τιμή στην 0-η γραμμή και 4-η στήλη. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Ορίζει μια τιμή στην 1-η γραμμή και 0-η στήλη. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Ορίζει μια τιμή στην 1-η γραμμή και 1-η στήλη. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Ορίζει μια τιμή στην 1-η γραμμή και 2-η στήλη. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Ορίζει μια τιμή στην 1-η γραμμή και 3-η στήλη. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Ορίζει μια τιμή στην 1-η γραμμή και 4-η στήλη. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Ορίζει μια τιμή στην 2-η γραμμή και 0-η στήλη. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Ορίζει μια τιμή στην 2-η γραμμή και 1-η στήλη. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Ορίζει μια τιμή στην 2-η γραμμή και 2-η στήλη. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Ορίζει μια τιμή στην 2-η γραμμή και 3-η στήλη. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Ορίζει μια τιμή στην 2-η γραμμή και 4-η στήλη. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Ορίζει μια τιμή στην 3-η γραμμή και 0-η στήλη. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Ορίζει μια τιμή στην 3-η γραμμή και 1-η στήλη. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Ορίζει μια τιμή στην 3-η γραμμή και 2-η στήλη. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Ορίζει μια τιμή στην 3-η γραμμή και 3-η στήλη. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Ορίζει μια τιμή στην 3-η γραμμή και 4-η στήλη. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Ορίζει μια τιμή στην 4-η γραμμή και 0-η στήλη. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Ορίζει μια τιμή στην 4-η γραμμή και 1-η στήλη. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Ορίζει μια τιμή στην 4-η γραμμή και 2-η στήλη. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Ορίζει μια τιμή στην 4-η γραμμή και 3-η στήλη. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Ορίζει μια τιμή στην 4-η γραμμή και 4-η στήλη. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό επιχειρησιακό όρισμα ως αδύναμο δείκτη (αντί για shared). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατό λειτουργικό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Κλήστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing::Imaging](../)
* Βιβλιοθήκη [Aspose.Slides](../../)