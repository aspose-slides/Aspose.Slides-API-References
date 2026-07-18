---
title: PathGradientBrush
second_title: Aspose.Slides για την Αναφορά API του C++
description: "Αντιπροσωπεύει ένα πινέλο που γεμίζει το εσωτερικό ενός αντικειμένου GraphicsPath με ένα διαβάθμισμα. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν τη κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 144
url: /el/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush κλάση

Αντιπροσωπεύει ένα πινέλο που γεμίζει το εσωτερικό ενός αντικειμένου [GraphicsPath](../graphicspath/) με ένα διαβαθμισμό. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργήσετε μια παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Δεν κάνει τίποτα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | Επιστρέφει ένα χρώμα που βρίσκεται στο κέντρο της διαδρομής που γεμίζει το τρέχον αντικείμενο. |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | Λαμβάνει το κεντρικό σημείο του διαβαθμισμού. |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | Λαμβάνει το σημείο εστίασης για την εξασθένιση του διαβαθμισμού. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | Επιστρέφει μια τιμή που ορίζει ένα πολυχρωμικό γραμμικό διαβαθμισμό. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | Επιστρέφει χρώματα που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](./). |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | Επιστρέφει ένα αντίγραφο ενός αντικειμένου [Matrix](../matrix/) που καθορίζει τις γεωμετρικές μετασχηματίσεις για το πινέλο που εκπροσωπείται από το τρέχον αντικείμενο. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | Επιστρέφει τη λειτουργία περιτύλιξης. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | Πολλαπλασιάζει τον πίνακα μετασχηματισμού του τρέχοντος αντικειμένου με τον καθορισμένο πίνακα. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | Δημιουργεί μια νέα παρουσία της κλάσης [PathGradientBrush](./). |
| [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | Δημιουργεί μια νέα παρουσία της κλάσης [PathGradientBrush](./). |
| [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | Δημιουργεί μια νέα παρουσία της κλάσης [PathGradientBrush](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [ResetTransform](./resettransform/)() | Επαναφέρει τον πίνακα μετασχηματισμού του τρέχοντος αντικειμένου ώστε να γίνει μητρώο ταυτότητας. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά την καθορισμένη γωνία με την καθορισμένη σειρά. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τους καθορισμένους παράγοντες με την καθορισμένη σειρά. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | Ορίζει ένα blend που καθορίζει τους παράγοντες και τις θέσεις των βασικών χρωμάτων για αυτό το πινέλο. |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | Ορίζει ένα χρώμα που βρίσκεται στο κέντρο της διαδρομής που γεμίζει το τρέχον αντικείμενο. |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | Ορίζει το κεντρικό σημείο του διαβαθμισμού. |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | Ορίζει το σημείο εστίασης για την εξασθένιση του διαβαθμισμού. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | Ορίζει μια τιμή που καθορίζει ένα πολυχρωμικό γραμμικό διαβαθμισμό. |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | Ορίζει χρώματα που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](./). |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | Ορίζει ένα αντικείμενο [Matrix](../matrix/) που καθορίζει τις γεωμετρικές μετασχηματίσεις για το πινέλο που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | Ορίζει τη λειτουργία περιτύλιξης. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Brush](../../system.drawing/brush/)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../)
* Βιβλιοθήκη [Aspose.Slides](../../)