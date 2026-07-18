---
title: Matrix
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει έναν πίνακα 3x3 που ορίζει λειτουργίες μετασχηματισμού. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 118
url: /el/system.drawing.drawing2d/matrix/
---
## Matrix κλάση


Αναπαριστά έναν πίνακα 3x3 που ορίζει λειτουργίες μετασχηματισμού. Τα αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας το operator new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτό το δείκτη για να το περάσετε σε λειτουργίες ως όρισμα.

```cpp
class Matrix : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου. |
| void [Dispose](./dispose/)() | Απελευθερώνει όλους τους πόρους του λειτουργικού συστήματος που αποκτήθηκαν από το τρέχον αντικείμενο. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Δοκιμάζει αν το καθορισμένο αντικείμενο είναι ένα [Matrix](./) και είναι ταυτόσημο με αυτό το αντικείμενο. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στο στυλ C# όπου δύο NaN θεωρούνται ίσα, παρά το ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στο στυλ C# όπου δύο NaN θεωρούνται ίσα, παρά το ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Επιστρέφει έναν πίνακα που περιέχει τα στοιχεία του πίνακα στην εξής σειρά: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Καθορίζει αν ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ένας πίνακας ταυτότητας. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Καθορίζει αν ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι αναστρέψιμος. |
| **float** [get_OffsetX](./get_offsetx/)() const | Επιστρέφει την τιμή μετάφρασης X του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **float** [get_OffsetY](./get_offsety/)() const | Επιστρέφει την τιμή μετάφρασης Y του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Αντιστρέφει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδώματος της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Δημιουργεί μια νέα παρουσία κλάσης [Matrix](./) που αντιπροσωπεύει έναν πίνακα ταυτότητας. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Δημιουργεί μια νέα παρουσία κλάσης [Matrix](./) και την αρχικοποιεί με τις καθορισμένες τιμές. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Δημιουργεί μια νέα παρουσία της κλάσης [Matrix](./) για τον γεωμετρικό μετασχηματισμό που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Δημιουργεί μια νέα παρουσία της κλάσης [Matrix](./) για τον γεωμετρικό μετασχηματισμό που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Πολλαπλασιάζει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο με τον καθορισμένο πίνακα. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Πολλαπλασιάζει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο με τον καθορισμένο πίνακα. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει πραγματικά τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει πραγματικά τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [Reset](./reset/)() | Επαναφέρει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο ώστε να γίνει πίνακας ταυτότητας. |
| void [Rotate](./rotate/)(**float**) | Περιστρέφει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο δεξιόστροφα κατά την καθορισμένη γωνία. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Περιστρέφει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο δεξιόστροφα γύρω από την προέλευση κατά την καθορισμένη γωνία. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Περιστρέφει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο δεξιόστροφα γύρω από το καθορισμένο σημείο κατά την καθορισμένη γωνία. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Περιστρέφει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο δεξιόστροφα γύρω από το καθορισμένο σημείο κατά την καθορισμένη γωνία. |
| void [Scale](./scale/)(**float**, **float**) | Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας στον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας στον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Εφαρμόζει το καθορισμένο διάνυσμα παραμόρφωσης (shear) στον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Εφαρμόζει το καθορισμένο διάνυσμα παραμόρφωσης (shear) στον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που ορίζεται από τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που ορίζεται από τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που ορίζεται από τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που ορίζεται από τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Εφαρμόζει μόνο τα στοιχεία κλίμακας και περιστροφής του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Εφαρμόζει μόνο τα στοιχεία κλίμακας και περιστροφής του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Εφαρμόζει μόνο τα στοιχεία κλίμακας και περιστροφής του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Εφαρμόζει μόνο τα στοιχεία κλίμακας και περιστροφής του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο στα καθορισμένα σημεία. |
| void [Translate](./translate/)(**float**, **float**) | Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης στον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης στον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εκδίπλωση (unlocking) της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Πολλαπλασιάζει κάθε διάνυσμα σε έναν πίνακα με τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Πολλαπλασιάζει κάθε διάνυσμα σε έναν πίνακα με τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../)
* Βιβλιοθήκη [Aspose.Slides](../../)