---
title: Region
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει το εσωτερικό ενός γραφικού σχήματος. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτήν την κλάση σε δείκτη System::SmartPtr pointer και χρησιμοποιείτε αυτόν το δείκτη για να το περάσετε σε functions as argument."
type: docs
weight: 261
url: /el/system.drawing/region/
---
## Region κλάση

Αντιπροσωπεύει το εσωτερικό ενός γραφικού σχήματος. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφαλματα ελέγχου. Πάντα περιβάλλετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάσετε σε λειτουργίες ως όρισμα.

```cpp
class Region : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Επιστρέφει ένα αντίγραφο του τρέχοντος αντικειμένου. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το τμήμα της περιοχής που ορίζεται από το καθορισμένο ορθογώνιο και δεν τέμνει αυτήν την περιοχή. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το τμήμα της περιοχής που ορίζεται από το καθορισμένο ορθογώνιο και δεν τέμνει αυτήν την περιοχή. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το τμήμα της περιοχής που ορίζεται από την καθορισμένη διαδρομή και δεν τέμνει αυτήν την περιοχή. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το τμήμα της καθορισμένης περιοχής που δεν τέμνει αυτήν την περιοχή. |
| void [Dispose](./dispose/)() | Απελευθερώνει όλους τους πόρους του λειτουργικού συστήματος που έχουν κτηθεί από το τρέχον αντικείμενο. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Καθορίζει εάν η καθορισμένη περιοχή είναι ταυτοτική με την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη επιφάνεια σχεδίασης. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ενώ σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ενώ σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της εξαίρεσης της περιοχής που ορίζεται από το καθορισμένο ορθογώνιο. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της εξαίρεσης της περιοχής που ορίζεται από το καθορισμένο ορθογώνιο. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της εξαίρεσης της περιοχής που ορίζεται από την καθορισμένη διαδρομή. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της εξαίρεσης της καθορισμένης περιοχής. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Λαμβάνει μια δομή [RectangleF](../rectanglef/) που αντιπροσωπεύει ένα ορθογώνιο που περιορίζει αυτό το [Region](./) στην επιφάνεια σχεδίασης ενός αντικειμένου [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει το hashing προσαρμοσμένων αντικειμένων. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Επιστρέφει ένα αντικείμενο RegionData που περιέχει τα δεδομένα που ορίζουν την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Επιστρέφει έναν πίνακα δομών [RectangleF](../rectanglef/) που προσεγγίζουν αυτό το [Region](./) μετά την εφαρμογή του συγκεκριμένου μετασχηματισμού πίνακα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της τομής αυτής της περιοχής με μια περιοχή που ορίζεται από το καθορισμένο ορθογώνιο. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της τομής αυτής της περιοχής με μια περιοχή που ορίζεται από το καθορισμένο ορθογώνιο. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της τομής αυτής της περιοχής με μια περιοχή που ορίζεται από την καθορισμένη διαδρομή. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της τομής αυτής της περιοχής με την καθορισμένη περιοχή. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο είναι μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# «is». |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Καθορίζει εάν η περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο έχει κενό εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Καθορίζει εάν η περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο έχει άπειρο εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Καθορίζει εάν το καθορισμένο σημείο περιέχεται μέσα στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Καθορίζει εάν το καθορισμένο σημείο περιέχεται μέσα στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Καθορίζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Καθορίζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Καθορίζει εάν το καθορισμένο σημείο περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τα καθορισμένα γραφικά. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Καθορίζει εάν το καθορισμένο σημείο περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τα καθορισμένα γραφικά. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Καθορίζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τα καθορισμένα γραφικά. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Καθορίζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τα καθορισμένα γραφικά. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Καθορίζει εάν το καθορισμένο σημείο περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Καθορίζει εάν το καθορισμένο σημείο περιέχεται στην περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τα καθορισμένα γραφικά. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή C# lock() κλειδώνοντας. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Αρχικοποιεί το τρέχον αντικείμενο με κενό εσωτερικό. |
| void [MakeInfinite](./makeinfinite/)() | Αρχικοποιεί αυτό το αντικείμενο περιοχής με άπειρο εσωτερικό. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστικό τελεστή ανάθεσης. Δεν αντιγράφει κάτι, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τιμή τύπου αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσωρών. |
|  [Region](./region/)() | Κατασκευάζει μια νέα παρουσία της κλάσης [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Κατασκευάζει μια νέα παρουσία της κλάσης [Region](./) που αντιπροσωπεύει μια περιοχή ορισμένη από το καθορισμένο ορθογώνιο. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Κατασκευάζει μια νέα παρουσία της κλάσης [Region](./) που αντιπροσωπεύει μια περιοχή ορισμένη από το καθορισμένο ορθογώνιο. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Κατασκευάζει μια νέα παρουσία της κλάσης [Region](./) που αντιπροσωπεύει μια περιοχή ορισμένη από την καθορισμένη διαδρομή. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Κατασκευάζει μια νέα παρουσία της κλάσης [Region](./) που αντιπροσωπεύει μια περιοχή ορισμένη από το αντικείμενο RegionData. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον αριθμό των κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Μετασχηματίζει αυτήν την περιοχή με τον καθορισμένο πίνακα. |
| void [Transform](./transform/)(const SkMatrix\&) | Μετασχηματίζει αυτήν την περιοχή με τον καθορισμένο πίνακα. |
| void [Translate](./translate/)(int, int) | Μετακινεί τις συντεταγμένες της περιοχής κατά την καθορισμένη ποσότητα. |
| void [Translate](./translate/)(**float**, **float**) | Μετακινεί τις συντεταγμένες της περιοχής κατά την καθορισμένη ποσότητα. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της ένωσης αυτής της περιοχής με μια περιοχή ορισμένη από το καθορισμένο ορθογώνιο. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της ένωσης αυτής της περιοχής με μια περιοχή ορισμένη από το καθορισμένο ορθογώνιο. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της ένωσης αυτής της περιοχής με μια περιοχή ορισμένη από την καθορισμένη διαδρομή. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με το αποτέλεσμα της ένωσης αυτής της περιοχής με την καθορισμένη περιοχή. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() αποκλεισμού. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αριθμό των αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αριθμό των αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με τα τμήματα αυτής της περιοχής και της περιοχής που ορίζεται από το καθορισμένο ορθογώνιο που δεν τέμνονται. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με τα τμήματα αυτής της περιοχής και της περιοχής που ορίζεται από το καθορισμένο ορθογώνιο που δεν τέμνονται. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με τα τμήματα αυτής της περιοχής και της περιοχής που ορίζεται από την καθορισμένη διαδρομή που δεν τέμνονται. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Αντικαθιστά την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο με τα τμήματα αυτής της περιοχής και της καθορισμένης περιοχής που δεν τέμνονται. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |
| virtual  [~Region](./~region/)() | Καταστροφέας. |

## See Also

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing](../)
* Βιβλιοθήκη [Aspose.Slides](../../)