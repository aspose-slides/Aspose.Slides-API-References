---
title: BulletFormat
second_title: Αναφορά API του Aspose.Slides για C++
description: Αντιπροσωπεύει τις ιδιότητες μορφοποίησης bullet παραγράφου.
type: docs
weight: 248
url: /el/aspose.slides/bulletformat/
---
## BulletFormat κλάση

Αντιπροσωπεύει τις ιδιότητες μορφοποίησης παραγράφων bullet.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Ορίζει τις προεπιλεγμένες μη-μηδενικές μετατοπίσεις για το αποτελεσματικό παράγραφο Indent και MarginLeft όταν τα bullets είναι ενεργοποιημένα (όπως κάνει το PowerPoint εάν ενεργοποιήσετε τα bullets/αρίθμηση παραγράφου σε αυτό). Εάν τα bullets είναι απενεργοποιημένα, τότε απλώς επαναφέρει το Indent και MarginLeft της παραγράφου (όπως κάνει το PowerPoint εάν απενεργοποιήσετε τα bullets/αρίθμηση παραγραφών σε αυτό). Οι μετατοπίσεις των εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο bullet - IBulletFormat::get(set)_Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη-μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (κάνουν τις τιμές αποτελέσματος τοπικές). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με το καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| char16_t [get_Char](./get_char/)() override | Επιστρέφει το χαρακτήρα bullet μιας παραγράφου χωρίς κληρονομικότητα. Διαβάστε **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Επιστρέφει τη μορφή χρώματος ενός bullet μιας παραγράφου χωρίς κληρονομικότητα. Μόνο-ανάγνωση [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Επιστρέφει τη γραμματοσειρά bullet μιας παραγράφου χωρίς κληρονομικότητα. Διαβάστε [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Επιστρέφει το ύψος bullet μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή std::numeric_limits<float>::quiet_NaN() καθορίζει ότι το bullet κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Διαβάστε **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Καθορίζει αν το bullet έχει δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει δικό του χρώμα και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Διαβάστε [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Καθορίζει αν το bullet έχει δική του γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει δική του γραμματοσειρά και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Διαβάστε [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Επιστρέφει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων bullets χωρίς κληρονομικότητα. Διαβάστε **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Επιστρέφει το στυλ ενός αριθμημένου bullet χωρίς κληρονομικότητα. Διαβάστε [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει τον γονέα [IPresentationComponent](../ipresentationcomponent/). Μόνο-ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Επιστρέφει την εικόνα που χρησιμοποιείται ως bullet σε μια παράγραφο χωρίς κληρονομικότητα. Μόνο-ανάγνωση [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Επιστρέφει τον τύπο bullet μιας παραγράφου χωρίς κληρονομικότητα. Διαβάστε [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης bullet με την εφαρμογή κληρονομικότητας. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδώση της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάδων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάδων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_Char](./set_char/)(char16_t) override | Ορίζει το χαρακτήρα bullet μιας παραγράφου χωρίς κληρονομικότητα. Γράψτε **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τη γραμματοσειρά bullet μιας παραγράφου χωρίς κληρονομικότητα. Γράψτε [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Ορίζει το ύψος bullet μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή std::numeric_limits<float>::quiet_NaN() καθορίζει ότι το bullet κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Γράψτε **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Καθορίζει αν το bullet έχει δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει δικό του χρώμα και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Γράψτε [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Καθορίζει αν το bullet έχει δική του γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **[NullableBool::True](../nullablebool/)** εάν το bullet έχει δική του γραμματοσειρά και **[NullableBool::False](../nullablebool/)** εάν το bullet κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην πρόγραφο. Γράψτε [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων bullets χωρίς κληρονομικότητα. Γράψτε **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Ορίζει το στυλ ενός αριθμημένου bullet χωρίς κληρονομικότητα. Γράψτε [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Ορίζει τον τύπο bullet μιας παραγράφου χωρίς κληρονομικότητα. Γράψτε [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εκδίκηση (unlocking) της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IBulletFormat](../ibulletformat/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)