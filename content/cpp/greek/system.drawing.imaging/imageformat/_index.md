---
title: ImageFormat
second_title: Aspose.Slides για την Αναφορά API C++
description: "Αναπαριστά τη μορφή αρχείου μιας εικόνας. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε εμφάνιση αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα λογικής. Πάντα τυλίγετε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε στις συναρτήσεις ως παράμετρο."
type: docs
weight: 131
url: /el/system.drawing.imaging/imageformat/
---
## ImageFormat κλάση

Αναπαριστά τη μορφή αρχείου μιας εικόνας. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε εμφάνιση αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα λογικής. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν το δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως παράμετρο.

```cpp
class ImageFormat : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Καθορίζει αν οι μορφές εικόνας που αντιπροσωπεύονται από το τρέχον και το καθορισμένο αντικείμενο είναι ίσες. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με το στυλ της C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή εικόνας bitmap. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή βελτιωμένου metafile. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή Exchangeable [Image](../../system.drawing/image/) File (Exif). |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή εικόνας [Graphics](../../system.drawing/graphics/) Interchange Format (GIF). |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Επιστρέφει το GUID που σχετίζεται με τη μορφή εικόνας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή εικόνας εικονιδίου [Windows](../../system.windows/). |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή εικόνας Joint Photographic Experts Group (JPEG). |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή ενός bitmap στη μνήμη. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή εικόνας W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG). |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή εικόνας Tagged [Image](../../system.drawing/image/) File Format (TIFF). |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | Επιστρέφει έναν κοινόχρηστο δείκτη προς ένα αντικείμενο [ImageFormat](./) που αντιπροσωπεύει τη μορφή μεταφίλ [Windows](../../system.windows/) (WMF). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | Δημιουργεί μια εμφάνιση της κλάσης [ImageFormat](./) που αντιπροσωπεύει μια μορφή εικόνας συνδεδεμένη με το καθορισμένο GUID. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από το targetType. Αναλογο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Μετατρέπει αυτό το αντικείμενο [ImageFormat](./) σε αναγνώσιμη για άνθρωπο συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκευαστικό τύπο C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing::Imaging](../)
* Βιβλιοθήκη [Aspose.Slides](../../)