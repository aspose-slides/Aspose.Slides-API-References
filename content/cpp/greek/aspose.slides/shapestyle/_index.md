---
title: ShapeStyle
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά την αναφορά στυλ του σχήματος.
type: docs
weight: 5149
url: /el/aspose.slides/shapestyle/
---
## ShapeStyle κλάση

Represent shape's style reference.

```cpp
class ShapeStyle : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Shape>>,
                   public Aspose::Slides::IShapeStyle
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() override | Επιστρέφει το χρώμα εφέ του σχήματος. Μόνο για ανάγνωση [IColorFormat](../icolorformat/). |
| **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() override | Επιστρέφει τον δείκτη στήλης εφέ του σχήματος σε μήτρα στυλ. Ανάγνωση **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() override | Επιστρέφει το χρώμα γεμίσματος του σχήματος. Μόνο για ανάγνωση [IColorFormat](../icolorformat/). |
| **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() override | Επιστρέφει τον δείκτη στήλης γεμίσματος του σχήματος σε μήτρες στυλ. 0 σημαίνει χωρίς γέμισμα, θετική τιμή – δείκτης στα στυλ γεμίσματος του θέματος, αρνητική τιμή – δείκτης στα στυλ φόντου του θέματος. Ανάγνωση **int16_t**. |
| [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() override | Επιστρέφει το δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματογραφιών. Ανάγνωση [Slides::FontCollectionIndex](../fontcollectionindex/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() override | Επιστρέφει το χρώμα γραμματοσειράς του σχήματος. Μόνο για ανάγνωση [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() override | Επιστρέφει το χρώμα περιγράμματος του σχήματος. Μόνο για ανάγνωση [IColorFormat](../icolorformat/). |
| **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() override | Επιστρέφει τον δείκτη στήλης γραμμής σε μια μήτρα στυλ. Ανάγνωση **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια υπόδειξη τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου προστασίας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) override | Ορίζει τον δείκτη στήλης εφέ του σχήματος σε μια μήτρα στυλ. Εγγραφή **uint32_t**. |
| void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) override | Ορίζει τον δείκτη στήλης γεμίσματος του σχήματος σε μήτρες στυλ. 0 σημαίνει χωρίς γέμισμα, θετική τιμή – δείκτης στα στυλ γεμίσματος του θέματος, αρνητική τιμή – δείκτης στα στυλ φόντου του θέματος. Εγγραφή **int16_t**. |
| void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) override | Ορίζει το δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. Εγγραφή [Slides::FontCollectionIndex](../fontcollectionindex/). |
| void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) override | Ορίζει τον δείκτη στήλης γραμμής σε μια μήτρα στυλ. Εγγραφή **uint16_t**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ορίζει το n-οστό όρισμα του πρότυπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου προστασίας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [DomObject](../domobject/)
* Κλάση [IShapeStyle](../ishapestyle/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)