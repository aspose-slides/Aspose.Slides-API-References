---
title: Pen
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει ιδιότητες όπως το χρώμα, το πλάτος κ.λπ. των γραμμών και των καμπύλων που σχεδιάζονται. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίγετε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 183
url: /el/system.drawing/pen/
---
## Pen κλάση

Αντιπροσωπεύει ιδιότητες όπως το χρώμα, το πλάτος κ.λπ. των γραμμών και των καμπυλών που σχεδιάζονται. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο με τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα.

```cpp
class Pen : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | Επιστρέφει ένα αντίγραφο του τρέχοντος αντικειμένου. |
| void [Dispose](./dispose/)() | Απελευθερώνει όλους τους λειτουργικούς πόρους που αποκτήθηκαν από το τρέχον αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με το στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με το στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρά το γεγονός ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρά το γεγονός ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | Επιστρέφει μια τιμή που υποδεικνύει την ευθυγράμμιση του τρέχοντος αντικειμένου [Pen](./). |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | Επιστρέφει το αντικείμενο [Brush](../brush/) αυτού του στυλό. |
| [Color](../color/) [get_Color](./get_color/)() const | Επιστρέφει το χρώμα αυτού του στυλό. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | Επιστρέφει έναν πίνακα τιμών που προσδιορίζει ένα σύνθετο στυλό. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | Επιστρέφει μια τιμή που υποδεικνύει το άκρο που χρησιμοποιείται και στις δύο άκρες μιας διακεκομένης γραμμής. |
| **float** [get_DashOffset](./get_dashoffset/)() const | Επιστρέφει την απόσταση από την αρχή μιας γραμμής έως την αρχή του μοτίβου διακεκομένης γραμμής. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | Επιστρέφει έναν πίνακα που υποδεικνύει το προσαρμοσμένο μοτίβο διακεκομένων γραμμών. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | Επιστρέφει μια τιμή που υποδεικνύει το στιλ διακεκομένης γραμμής του τρέχοντος αντικειμένου [Pen](./). |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | Επιστρέφει μια τιμή που υποδεικνύει το άκρο λήξης της γραμμής του τρέχοντος αντικειμένου [Pen](./). |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | Επιστρέφει μια τιμή που υποδεικνύει πώς ενώνονται οι γραμμές που σχεδιάζονται από αυτό το αντικείμενο [Pen](./). |
| **float** [get_MiterLimit](./get_miterlimit/)() const | Επιστρέφει το όριο του πάχους της ένωσης σε γωνία μανίκου. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | Επιστρέφει μια τιμή που υποδεικνύει το αρχικό άκρο της γραμμής του τρέχοντος αντικειμένου [Pen](./). |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | Επιστρέφει ένα αντίγραφο ενός αντικειμένου Matrix που καθορίζει τις γεωμετρικές μετασχηματισμούς για το στυλό που αναπαρίσταται από το τρέχον αντικείμενο. |
| **float** [get_Width](./get_width/)() const | Επιστρέφει το πλάτος του τρέχοντος αντικειμένου [Pen](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Πολλαπλασιάζει τον μετασχηματιστικό πίνακα του τρέχοντος αντικειμένου με τον καθορισμένο πίνακα. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφου σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφου σε υποκλάσεις. |
|  [Pen](./pen/)(const [Color](../color/)\&) | Κατασκευάζει ένα νέο αντικείμενο [Pen](./) που αντιπροσωπεύει το καθορισμένο χρώμα. |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | Κατασκευάζει ένα νέο αντικείμενο [Pen](./) που αντιπροσωπεύει το καθορισμένο χρώμα και πλάτος. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Κατασκευάζει ένα νέο αντικείμενο [Pen](./) και το αρχικοποιεί με το καθορισμένο αντικείμενο [Brush](../brush/). |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | Κατασκευάζει ένα νέο αντικείμενο [Pen](./) και το αρχικοποιεί με το καθορισμένο αντικείμενο [Brush](../brush/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει την αναφορά ενός αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [ResetTransform](./resettransform/)() | Επαναφέρει τον μετασχηματιστικό πίνακα του τρέχοντος αντικειμένου ώστε να γίνει ταυτοτικός πίνακας. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη συγκεκριμένη γωνία με την καθορισμένη σειρά. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Κάνει κλίμακα του τοπικού γεωμετρικού μετασχηματισμού με τους καθορισμένους παράγοντες με την καθορισμένη σειρά. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | Ορίζει την ευθυγράμμιση του τρέχοντος αντικειμένου [Pen](./). |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Ορίζει το αντικείμενο [Brush](../brush/) αυτού του στυλό. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | Ορίζει το χρώμα αυτού του στυλό. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Ορίζει έναν πίνακα τιμών που προσδιορίζει ένα σύνθετο στυλό. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Ορίζει το προσαρμοσμένο άκρο λήξης γραμμής. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Ορίζει το προσαρμοσμένο άκρο έναρξης γραμμής. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | Ορίζει μια τιμή που καθορίζει το άκρο που χρησιμοποιείται και στις δύο άκρες μιας διακεκομένης γραμμής. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | Ορίζει την απόσταση από την αρχή μιας γραμμής έως την αρχή του μοτίβου διακεκομένης γραμμής. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Ορίζει έναν πίνακα που καθορίζει προσαρμοσμένο μοτίβο διακεκομένων γραμμών. Ο πίνακας αποτελείται από αριθμούς που καθορίζουν τα μήκη εναλλασσόμενων παύλων και κενών. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | Ορίζει μια τιμή που καθορίζει το στιλ διακεκομένης γραμμής του τρέχοντος αντικειμένου [Pen](./). |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Ορίζει το άκρο λήξης της γραμμής του τρέχοντος αντικειμένου [Pen](./). |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | Ορίζει μια τιμή που καθορίζει πώς ενώνονται οι γραμμές που σχεδιάζονται από αυτό το αντικείμενο [Pen](./). |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | Ορίζει το όριο του πάχους της ένωσης σε γωνία μανίκου. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Ορίζει το αρχικό άκρο γραμμής του τρέχοντος αντικειμένου [Pen](./). |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Ορίζει ένα αντικείμενο Matrix που καθορίζει τους γεωμετρικούς μετασχηματισμούς για το στυλό που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [set_Width](./set_width/)(**float**) | Ορίζει το πλάτος του τρέχοντος αντικειμένου [Pen](./). |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την εκ απαγόρευσης της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing](../)
* Βιβλιοθήκη [Aspose.Slides](../../)