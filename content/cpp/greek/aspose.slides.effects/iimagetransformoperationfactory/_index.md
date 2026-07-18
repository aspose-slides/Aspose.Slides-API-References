---
title: IImageTransformOperationFactory
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιτρέπει τη δημιουργία στιγμιοτύπων εφέ εικόνας
type: docs
weight: 755
url: /el/aspose.slides.effects/iimagetransformoperationfactory/
---
## IImageTransformOperationFactory κλάση


Allows to create image effects' instances

```cpp
class IImageTransformOperationFactory : public virtual System::Object
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [CreateAlphaBiLevel](./createalphabilevel/)(**float**) | Δημιουργεί Alpha [BiLevel](../bilevel/) εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [CreateAlphaFloor](./createalphafloor/)() | Δημιουργεί Alpha floor εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [CreateAlphaInverse](./createalphainverse/)() | Δημιουργεί Alpha inverse εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [CreateAlphaModulate](./createalphamodulate/)() | Δημιουργεί Alpha modulate εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [CreateAlphaModulateFixed](./createalphamodulatefixed/)(**float**) | Δημιουργεί Alpha modulate fixed εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [CreateAlphaReplace](./createalphareplace/)(**float**) | Δημιουργεί Alpha replace εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [CreateAlphCeiling](./createalphceiling/)() | Δημιουργεί Alpha Ceiling εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [CreateBiLevel](./createbilevel/)(**float**) | Δημιουργεί [BiLevel](../bilevel/) εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [CreateBlur](./createblur/)(**double**, **bool**) | Δημιουργεί [Blur](../blur/) εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [CreateColorChange](./createcolorchange/)() | Δημιουργεί Color change εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [CreateColorReplace](./createcolorreplace/)() | Δημιουργεί Color replace εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [CreateDuotone](./createduotone/)() | Δημιουργεί [Duotone](../duotone/) εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [CreateFillOverlay](./createfilloverlay/)() | Δημιουργεί Fill overlay εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [CreateGrayScale](./creategrayscale/)() | Δημιουργεί Gray scale εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [CreateHSL](./createhsl/)(**float**, **float**, **float**) | Δημιουργεί Hue Saturation [Luminance](../luminance/) εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [CreateLuminance](./createluminance/)(**float**, **float**) | Δημιουργεί [Luminance](../luminance/) εφέ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [CreateTint](./createtint/)(**float**, **float**) | Δημιουργεί [Tint](../tint/) εφέ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας C# [Object.Equals](../../system/object/equals/) σημασιολογία. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση του string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει τη μετατροπή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Παρατηρήσεις


Για διεπαφή COM. 
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Effects](../)
* Βιβλιοθήκη [Aspose.Slides](../../)