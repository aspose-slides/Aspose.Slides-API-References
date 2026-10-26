---
title: OuterShadow
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεύει ένα εφέ εξωτερικής σκιάς.
type: docs
weight: 1041
url: /el/aspose.slides.effects/outershadow/
---
## OuterShadow κλάση

Αντιπροσωπεύει ένα εφέ Outer Shadow.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Καθορίζει εάν το καθορισμένο [OuterShadow](./) είναι ίσο με το τρέχον [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) ακτίνα, σε σημεία. Προεπιλεγμένη τιμή – 0 pt. Ανάγνωση **double**. |
| **float** [get_Direction](./get_direction/)() override | Κατεύθυνση της σκιάς, σε μοίρες. Προεπιλεγμένη τιμή – 0 ° (αριστερά προς δεξιά). Ανάγνωση **float**. |
| **double** [get_Distance](./get_distance/)() override | Απόσταση της σκιάς από το αντικείμενο, σε σημεία. Προεπιλεγμένη τιμή – 0 pt. Ανάγνωση **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονικό [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Μόνο ανάγνωση [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Ευθυγράμμιση ορθογωνίου. Προεπιλεγμένη τιμή – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Ανάγνωση [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Δείχνει εάν η σκιά περιστρέφεται μαζί με το σχήμα. Προεπιλεγμένη τιμή – true. Ανάγνωση **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Οριζόντιος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή – 100 %. Ανάγνωση **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Κατακόρυφος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή – 100 %. Ανάγνωση **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Χρώμα της σκιάς. Προεπιλεγμένη τιμή – αυτόματο μαύρο (εξαρτάται από το θέμα). Μόνο ανάγνωση [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Οριζόντια γωνία στριφογύρισης, σε μοίρες. Προεπιλεγμένη τιμή – 0 °. Ανάγνωση **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Κατακόρυφη γωνία στριφογύρισης, σε μοίρες. Προεπιλεγμένη τιμή – 0 °. Ανάγνωση **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Έκδοση. Μόνο ανάγνωση **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Outer Shadow με την κληρονομικότητα εφαρμοσμένη. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου εποπτείας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων των υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) ακτίνα, σε σημεία. Προεπιλεγμένη τιμή – 0 pt. Εγγραφή **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Κατεύθυνση της σκιάς, σε μοίρες. Προεπιλεγμένη τιμή – 0 ° (αριστερά προς δεξιά). Εγγραφή **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Απόσταση της σκιάς από το αντικείμενο, σε σημεία. Προεπιλεγμένη τιμή – 0 pt. Εγγραφή **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Ευθυγράμμιση ορθογωνίου. Προεπιλεγμένη τιμή – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Εγγραφή [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Δείχνει εάν η σκιά περιστρέφεται μαζί με το σχήμα. Προεπιλεγμένη τιμή – true. Εγγραφή **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Οριζόντιος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή – 100 %. Εγγραφή **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Κατακόρυφος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή – 100 %. Εγγραφή **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Οριζόντια γωνία στριφογύρισης, σε μοίρες. Προεπιλεγμένη τιμή – 0 °. Εγγραφή **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Κατακόρυφη γωνία στριφογύρισης, σε μοίρες. Προεπιλεγμένη τιμή – 0 °. Εγγραφή **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί לכך, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί לכך, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εκδρόση της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου εποπτείας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί לכך, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί بذلك, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IOuterShadow](../ioutershadow/)
* Κλάση [IVisualEffect](../ivisualeffect/)
* Κλάση [IPVIObject](../../aspose.slides/ipviobject/)
* Χώρος ονομάτων [Aspose::Slides::Effects](../)
* Βιβλιοθήκη [Aspose.Slides](../../)