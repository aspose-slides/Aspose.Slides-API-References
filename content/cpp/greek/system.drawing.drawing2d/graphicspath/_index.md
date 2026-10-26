---
title: GraphicsPath
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει ένα σύνολο συνδεδεμένων γραμμών και καμπυλών. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε αντίτυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτήν την κλάση με δείκτη System::SmartPtr pointer και χρησιμοποιήστε αυτόν τον δείκτη για να το μεταβιβάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 66
url: /el/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath κλάση

Αντιπροσωπεύει ένα σύνολο συνδεδεμένων γραμμών και καμπυλών. Τα αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε αντίτυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτήν την κλάση με δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα.

```cpp
class GraphicsPath : public System::Object
```

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Προσθέτει το καθορισμένο ελλειπτικό τόξο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Προσθέτει το καθορισμένο ελλειπτικό τόξο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Προσθέτει το καθορισμένο ελλειπτικό τόξο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Προσθέτει το καθορισμένο ελλειπτικό τόξο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Προσθέτει τη συγκεκριμένη κυβική καμπύλη Bezier στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Προσθέτει τη συγκεκριμένη κυβική καμπύλη Bezier στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Προσθέτει τη συγκεκριμένη κυβική καμπύλη Bezier στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Προσθέτει τη συγκεκριμένη κυβική καμπύλη Bezier στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Προσθέτει μια ακολουθία συνδεδεμένων κυβικών καμπυλών Bezier στο τρέχον σχήμα. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Προσθέτει μια ακολουθία συνδεδεμένων κυβικών καμπυλών Bezier στο τρέχον σχήμα. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Προσθέτει την καθορισμένη κλειστή καμπύλη στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Προσθέτει την καθορισμένη κλειστή καμπύλη στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Προσθέτει την καθορισμένη καμπύλη στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Προσθέτει την καθορισμένη καμπύλη στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Προσθέτει την καθορισμένη καμπύλη στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Προσθέτει την καθορισμένη καμπύλη στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Προσθέτει το καθορισμένο έλλειψο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Προσθέτει το καθορισμένο έλλειψο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Προσθέτει το καθορισμένο έλλειψο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Προσθέτει το καθορισμένο έλλειψο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Προσθέτει την καθορισμένη γραμμή στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Προσθέτει την καθορισμένη γραμμή στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddLine](./addline/)(int, int, int, int) | Προσθέτει την καθορισμένη γραμμή στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Προσθέτει την καθορισμένη γραμμή στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Προσθέτει τη συγκεκριμένη σειρά συνδεδεμένων τμημάτων γραμμής στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Προσθέτει τη συγκεκριμένη σειρά συνδεδεμένων τμημάτων γραμμής στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Προσθέτει τη συγκεκριμένη διαδρομή στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Προσθέτει το καθορισμένο περίγραμμα του σχήματος πίτας στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Προσθέτει το καθορισμένο περίγραμμα του σχήματος πίτας στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Προσθέτει το καθορισμένο περίγραμμα του σχήματος πίτας στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Προσθέτει το καθορισμένο πολύγωνο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Προσθέτει το καθορισμένο πολύγωνο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Προσθέτει το καθορισμένο ορθογώνιο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Προσθέτει το καθορισμένο ορθογώνιο στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Προσθέτει μια σειρά ορθογώνιων στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Προσθέτει μια σειρά ορθογώνιων στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Προσθέτει μια συμβολοσειρά κειμένου στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Προσθέτει μια συμβολοσειρά κειμένου στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Προσθέτει μια συμβολοσειρά κειμένου στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Προσθέτει μια συμβολοσειρά κειμένου στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου. |
| void [CloseAllFigures](./closeallfigures/)() | Κλείνει όλα τα ανοιχτά σχήματα και ξεκινά ένα νέο. |
| void [CloseFigure](./closefigure/)() | Κλείνει το τρέχον σχήμα και ξεκινά ένα νέο. |
| void [Dispose](./dispose/)() | Απελευθερώνει όλους τους πόρους του λειτουργικού συστήματος που καταναλώθηκαν από το τρέχον αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη λογική του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρ'όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρ'όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Για εσωτερικούς σκοπούς μόνο. |
| void [Flatten](./flatten/)() | Ιστώνει κάθε καμπύλη στη διαδρομή μετατρέποντάς την σε μια σειρά συνδεδεμένων γραμμών. Η τιμή ιστώνειας είναι 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Ιστώνει κάθε καμπύλη στη διαδρομή μετατρέποντάς την σε μια σειρά συνδεδεμένων γραμμών. Η τιμή ιστώνειας είναι 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Ιστώνει κάθε καμπύλη στη διαδρομή μετατρέποντάς την σε μια σειρά συνδεδεμένων γραμμών. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Επιστρέφει τη λειτουργία γεμίσματος του τρέχοντος αντικειμένου. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Επιστρέφει ένα [PathData](../pathdata/) αντικείμενο που περιέχει τα σημεία που κάνουν τη διαδρομή όπως εκφράζεται από το τρέχον αντικείμενο και τους τύπους τους. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Επιστρέφει έναν πίνακα που περιέχει τα σημεία που κάνουν τη διαδρομή όπως εκφράζεται από το τρέχον αντικείμενο. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Επιστρέφει έναν πίνακα που περιέχει τιμές που υποδεικνύουν τους τύπους των σημείων που κάνουν τη διαδρομή όπως εκφράζεται από το τρέχον αντικείμενο. |
| int [get_PointCount](./get_pointcount/)() const | Επιστρέφει τον αριθμό των σημείων στη διαδρομή που εκφράζεται από το τρέχον αντικείμενο. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Επιστρέφει ένα [RectangleF](../../system.drawing/rectanglef/) αντικείμενο που αντιπροσωπεύει ένα ορθογώνιο που περικλείει τη διαδρομή όπως εκφράζεται από το τρέχον αντικείμενο όταν μετασχηματίζεται με τον καθορισμένο πίνακα. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Επιστρέφει μια τιμή που είναι ένας δυαδικός συνδυασμός τιμών Detail::FigureType που υποδεικνύει ποιοι τύποι σχημάτων περιέχονται στη διαδρομή όπως εκφράζεται από το τρέχον αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Επιστρέφει ένα [PointF](../../system.drawing/pointf/) αντικείμενο που αντιπροσωπεύει το τελευταίο σημείο στη διαδρομή. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Δημιουργεί μια νέα παρουσία της κλάσης [GraphicsPath](./) με τη καθορισμένη λειτουργία γεμίσματος. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Δημιουργεί μια νέα παρουσία του αντικειμένου [GraphicsPath](./) που αντιπροσωπεύει τη συγκεκριμένη διαδρομή. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Δημιουργεί μια νέα παρουσία του αντικειμένου [GraphicsPath](./) που αντιπροσωπεύει τη συγκεκριμένη διαδρομή. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Δείχνει αν το καθορισμένο σημείο περιέχεται μέσα (κάτω) από το περίγραμμα αυτού του [GraphicsPath](./) όταν σχεδιάζεται με το καθορισμένο [Pen](../../system.drawing/pen/). ΔΕΝ Υλοποιείται. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα στη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέας ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τιμής τύπου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [Reset](./reset/)() | Αδειάζει τη διαδρομή αφαιρώντας όλα τα σημεία από αυτήν. |
| void [Reverse](./reverse/)() | Αντιστρέφει τη σειρά των σημείων στον πίνακα PathPoints αυτού του [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Ορίζει τη λειτουργία γεμίσματος του τρέχοντος αντικειμένου. |
| void [SetMarkers](./setmarkers/)() | ΔΕΝ Υλοποιείται. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δομές σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [StartFigure](./startfigure/)() | Ξεκινά ένα νέο σχήμα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Μετασχηματίζει τη διαδρομή που εκπροσωπείται από το τρέχον αντικείμενο εφαρμόζοντας τον καθορισμένο πίνακα μετασχηματισμού. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του C# lock() statement. Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Αντικαθιστά αυτή τη διαδρομή με ένα περίγραμμα γύρω από την αρχική διαδρομή. |
|  [~GraphicsPath](./~graphicspath/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../)
* Βιβλιοθήκη [Aspose.Slides](../../)