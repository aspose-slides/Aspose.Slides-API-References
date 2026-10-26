---
title: ImageAttributes
second_title: Αναφορά API του Aspose.Slides για C++
description: "Αναπαριστά πληροφορίες σχετικά με το πώς τα χρώματα της εικόνας διαχειρίζονται κατά την απόδοση. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή με χρήση του τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα διαβεβαίωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να τον περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 105
url: /el/system.drawing.imaging/imageattributes/
---
## ImageAttributes κλάση

Αναπαριστά πληροφορίες σχετικά με το πώς τα χρώματα εικόνας χειρίζονται κατά την απόδοση. Αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο με τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας operator new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα διαβεβαίωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε στις συναρτήσεις ως όρισμα.

```cpp
class ImageAttributes : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [ClearBrushRemapTable](./clearbrushremaptable/)() | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearColorKey](./clearcolorkey/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearColorMatrix](./clearcolormatrix/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearGamma](./cleargamma/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearNoOp](./clearnoop/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearOutputChannel](./clearoutputchannel/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearRemapTable](./clearremaptable/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [ClearThreshold](./clearthreshold/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| [SharedPtr](../../system/sharedptr/)\<[ImageAttributes](./)\> [Clone](./clone/)() | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου. |
| void [Dispose](./dispose/)() | Απελευθερώνει όλους τους πόρους του λειτουργικού συστήματος που έχουν αποκτηθεί από το τρέχον αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| void [GetAdjustedPalette](./getadjustedpalette/)(const [SharedPtr](../../system/sharedptr/)\<[ColorPalette](../colorpalette/)\>\&, [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ImageAttributes](./imageattributes/)() | Κατασκευαστής προεπιλογής. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια έκδοση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [SetBrushRemapTable](./setbrushremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetColorKey](./setcolorkey/)([Color](../../system.drawing/color/), [Color](../../system.drawing/color/), [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetColorMatrices](./setcolormatrices/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetColorMatrix](./setcolormatrix/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | Ορίζει τον πίνακα ρυθμίσεων χρώματος. |
| void [SetGamma](./setgamma/)(**float**, [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetNoOp](./setnoop/)([ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetOutputChannel](./setoutputchannel/)([ColorChannelFlag](../colorchannelflag/), [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const [String](../../system/string/)\&, [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetRemapTable](./setremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&, [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| void [SetThreshold](./setthreshold/)(**float**, [ColorAdjustType](../coloradjusttype/)) | ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ. |
| void [SetWrapMode](./setwrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Color](../../system.drawing/color/), **bool**) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για τον καθορισμό του τρόπου επικάλυψης μιας υφής σε ένα σχήμα ή στα όρια του σχήματος. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing::Imaging](../)
* Βιβλιοθήκη [Aspose.Slides](../../)