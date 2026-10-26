---
title: ITextFrameFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Περιέχει τις ιδιότητες μορφοποίησης του TextFrame.
type: docs
weight: 4083
url: /el/aspose.slides/itextframeformat/
---
## ITextFrameFormat κλάση


Περιέχει τις ιδιότητες μορφοποίησης του [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Επιστρέφει το κείμενο κατακόρυφης άγκυρας σε ένα [TextFrame](../textframe/). Διαβάστε [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Επιστρέφει τη λειτουργία αυτόματης προσαρμογής του κειμένου. Διαβάστε [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Εάν [NullableBool::True](../nullablebool/) τότε το κείμενο πρέπει να ευθυγραμμίζεται κεντρικά οριζόντια στο πλαίσιο. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Επιστρέφει τον αριθμό των στηλών στην περιοχή κειμένου. Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Διαβάστε **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Επιστρέφει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Αυτό πρέπει να ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή αυτή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Διαβάστε **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Επιστρέφει ή ορίζει τη διατήρηση του κειμένου εντελώς εκτός 3Δ σκηνής. Διαβάστε **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Επιστρέφει το κάτω περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Επιστρέφει το αριστερό περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Επιστρέφει το δεξιό περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Επιστρέφει το άνω περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο οριοθετημένο πλαίσιο. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, τότε εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προεπιλεγμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Διαβάστε **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Επιστρέφει το στυλ του κειμένου. Μόνο για ανάγνωση [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προσαρμοσμένο γωνιακό συντελεστή στην ιδιότητα RotationAngle. Διαβάστε [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που αντιπροσωπεύει τις ιδιότητες 3Δ εφέ για ένα κείμενο. Μόνο για ανάγνωση [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Λαμβάνει το σχήμα αναδίπλωσης κειμένου. Διαβάστε [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **Αληθές** εάν το κείμενο αναδιπλώνεται στα περιθώρια του [TextFrame](../textframe/). Διαβάστε [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης πλαισίου κειμένου με την κληρονομικότητα εφαρμόστηκε. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τον κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια υπόδειξη τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, μόνο αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, μόνο αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά τη συγκεκριμένη τιμή. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Ορίζει το κείμενο κατακόρυφης άγκυρας σε ένα [TextFrame](../textframe/). Γράψτε [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Ορίζει τη λειτουργία αυτόματης προσαρμογής του κειμένου. Γράψτε [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Εάν [NullableBool::True](../nullablebool/) τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο πλαίσιο. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Γράψτε **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Αυτό ισχύει μόνο όταν υπάρχει παραπάνω από 1 στήλη. Η τιμή αυτή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Γράψτε **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Επιστρέφει ή ορίζει τη διατήρηση του κειμένου εντελώς εκτός σκηνής 3D. Γράψτε **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ορίζει το κάτω περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ορίζει το αριστερό περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ορίζει το δεξιό περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ορίζει το άνω περιθώριο (σημεία) σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο οριοθετημένο πλαίσιο. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, τότε εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προεπιλεγμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Γράψτε **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προσαρμοσμένο γωνιακό συντελεστή στην ιδιότητα RotationAngle. Γράψτε [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Ορίζει το σχήμα αναδίπλωσης κειμένου. Γράψτε [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **Αληθές** εάν το κείμενο αναδιπλώνεται στα περιθώρια του [TextFrame](../textframe/). Γράψτε [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει τη κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την απελευθέρωση της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)