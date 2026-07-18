---
title: IOuterShadow
second_title: Aspose.Slides για την Αναφορά API C++
description: Αντιπροσωπεύει ένα εφέ εξωτερικής σκιάς.
type: docs
weight: 885
url: /el/aspose.slides.effects/ioutershadow/
---
## IOuterShadow κλάση

Αντιπροσωπεύει ένα εξωτερικό εφέ σκιάς.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) ακτίνα, σε σημεία. Προεπιλεγμένη τιμή \u2013 0 pt. Ανάγνωση **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Κατεύθυνση της σκιάς, σε μοίρες. Προεπιλεγμένη τιμή \u2013 0 \u00B0 (από αριστερά προς δεξιά). Ανάγνωση **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Απόσταση της σκιάς από το αντικείμενο, σε σημεία. Προεπιλεγμένη τιμή \u2013 0 pt. Ανάγνωση **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Στοίχιση ορθογωνίου. Προεπιλεγμένη τιμή \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Ανάγνωση [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Δείχνει αν η σκιά περιστρέφεται μαζί με το σχήμα. Προεπιλεγμένη τιμή \u2013 true. Ανάγνωση **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Οριζόντιος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή \u2013 100 %. Ανάγνωση **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Κάθετος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή \u2013 100 %. Ανάγνωση **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Χρώμα της σκιάς. Προεπιλεγμένη τιμή \u2013 αυτόματο μαύρο (εξαρτάται από το θέμα). Μόνο ανάγνωση [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Οριζόντια γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή \u2013 0 \u00B0. Ανάγνωση **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Κάθετη γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή \u2013 0 \u00B0. Ανάγνωση **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Λαμβάνει τα αποτελεσματικά δεδομένα με την κληρονομικότητα εφαρμοσμένη. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευή αντιγράφου. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξαίρεση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξαίρεση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) ακτίνα, σε σημεία. Προεπιλεγμένη τιμή \u2013 0 pt. Εγγραφή **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Κατεύθυνση της σκιάς, σε μοίρες. Προεπιλεγμένη τιμή \u2013 0 \u00B0 (από αριστερά προς δεξιά). Εγγραφή **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Απόσταση της σκιάς από το αντικείμενο, σε σημεία. Προεπιλεγμένη τιμή \u2013 0 pt. Εγγραφή **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Στοίχιση ορθογωνίου. Προεπιλεγμένη τιμή \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Εγγραφή [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Δείχνει αν η σκιά περιστρέφεται μαζί με το σχήμα. Προεπιλεγμένη τιμή \u2013 true. Εγγραφή **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Οριζόντιος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή \u2013 100 %. Εγγραφή **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Κάθετος συντελεστής κλιμάκωσης, σε ποσοστό του αρχικού μεγέθους. Η αρνητική κλιμάκωση προκαλεί αναστροφή. Προεπιλεγμένη τιμή \u2013 100 %. Εγγραφή **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Οριζόντια γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή \u2013 0 \u00B0. Εγγραφή **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Κάθετη γωνία παραμόρφωσης, σε μοίρες. Προεπιλεγμένη τιμή \u2013 0 \u00B0. Εγγραφή **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει την n'tη παράμετρο προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IImageTransformOperation](../iimagetransformoperation/)
* Κλάση [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Χώρος ονομάτων [Aspose::Slides::Effects](../)
* Βιβλιοθήκη [Aspose.Slides](../../)