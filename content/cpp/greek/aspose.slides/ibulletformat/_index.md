---
title: IBulletFormat
second_title: Aspose.Slides για την αναφορά API του C++
description: Αναπαριστά τις ιδιότητες μορφοποίησης σφαίρας παραγράφου.
type: docs
weight: 1561
url: /el/aspose.slides/ibulletformat/
---
## IBulletFormat κλάση

Αναπαριστά τις ιδιότητες μορφοποίησης σφαίρας παραγράφου.

```cpp
class IBulletFormat : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Ορίζει τις προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν τα bullets είναι ενεργά (όπως κάνει το PowerPoint όταν ενεργοποιείται η μορφοποίηση/αρίθμηση bullets στην παράγραφο). Αν τα bullets είναι απενεργοποιημένα, τότε απλώς επαναφέρει το Indent και MarginLeft της παραγράφου (όπως κάνει το PowerPoint όταν απενεργοποιείται η μορφοποίηση/αρίθμηση bullets). Οι μετατοπίσεις των εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο bullet - IBulletFormat::get(set)_Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (καθιστώντας τις τιμές αποτέλεσμα τοπικές). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual char16_t [get_Char](./get_char/)() | Επιστρέφει το χαρακτήρα bullet μιας παραγράφου χωρίς κληρονομιά. Ανάγνωση **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Επιστρέφει τη μορφή χρώματος ενός bullet μιας παραγράφου χωρίς κληρονομιά. Ανάγνωση-μόνο [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Επιστρέφει τη γραμματοσειρά bullet μιας παραγράφου χωρίς κληρονομιά. Ανάγνωση [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Επιστρέφει το ύψος bullet μιας παραγράφου χωρίς κληρονομιά. Η τιμή std::numeric_limits<float>::quiet_NaN() καθορίζει ότι το bullet κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Καθορίζει αν το bullet έχει το δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει το δικό του χρώμα και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Καθορίζει αν το bullet έχει τη δική του γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει τη δική του γραμματοσειρά και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Επιστρέφει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων bullets χωρίς κληρονομιά. Ανάγνωση **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Επιστρέφει το στυλ ενός αριθμημένου bullet χωρίς κληρονομιά. Ανάγνωση [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Επιστρέφει την εικόνα που χρησιμοποιείται ως bullet σε μια παράγραφο χωρίς κληρονομιά. Ανάγνωση-μόνο [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Επιστρέφει τον τύπο bullet μιας παραγράφου χωρίς κληρονομιά. Ανάγνωση [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης bullet με την κληρονομιά εφαρμοσμένη. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος της C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση της C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικός τελεστής C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει τη δήλωση κλειδώματος lock() της C#. Καλείτε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμετρο αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Char](./set_char/)(char16_t) | Ορίζει το χαρακτήρα bullet μιας παραγράφου χωρίς κληρονομιά. Εγγραφή **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ορίζει τη γραμματοσειρά bullet μιας παραγράφου χωρίς κληρονομιά. Εγγραφή [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Ορίζει το ύψος bullet μιας παραγράφου χωρίς κληρονομιά. Η τιμή std::numeric_limits<float>::quiet_NaN() καθορίζει ότι το bullet κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Εγγραφή **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Καθορίζει αν το bullet έχει το δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει το δικό του χρώμα και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Εγγραφή [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Καθορίζει αν το bullet έχει τη δική του γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει τη δική του γραμματοσειρά και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Εγγραφή [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων bullets χωρίς κληρονομιά. Εγγραφή **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Ορίζει το στυλ ενός αριθμημένου bullet χωρίς κληρονομιά. Εγγραφή [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Ορίζει τον τύπο bullet μιας παραγράφου χωρίς κληρονομιά. Εγγραφή [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυσώπη δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυσώπη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμετρου αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμετρο αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμετρο αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος της C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης lock() της C#. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυσώπη μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυσώπη μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)