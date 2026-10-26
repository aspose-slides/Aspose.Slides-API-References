---
title: IChartTitle
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναπαριστά τις ιδιότητες του τίτλου διαγράμματος.
type: docs
weight: 911
url: /el/aspose.slides.charts/icharttitle/
---
## IChartTitle κλάση

Αναπαριστά τις ιδιότητες του τίτλου γραφήματος.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Καθορίζει το πραγματικό ύψος του στοιχείου γραφήματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Καθορίζει το πραγματικό πλάτος του στοιχείου γραφήματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου γραφήματος σε σχέση με την αριστερή άνω γωνία του γραφήματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου γραφήματος σε σχέση με την αριστερή άνω γωνία του γραφήματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Παίρνει το πάνω μέρος του στοιχείου γραφήματος ως κλασματικό του ύψους του γραφήματος. Μόνο-ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το γράφημα. Μόνο-ανάγνωση [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Επιστρέφει τα στυλ γεμίσματος, γραμμής, εφέ ενός τίτλου. Μόνο-ανάγνωση [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Καθορίζει το ύψος του στοιχείου γραφήματος ως κλασματικό του ύψους του γραφήματος. Ανάγνωση **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Καθορίζει αν άλλα στοιχεία γραφήματος θα επιτρέπεται να επικαλύπτουν τον τίτλο. Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο-ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Παίρνει το δεξί μέρος του στοιχείου γραφήματος ως κλασματικό του πλάτους του γραφήματος. Μόνο-ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο-ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Επιστρέφει τη μορφή κειμένου γραφήματος. Μόνο-ανάγνωση [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου παρακάμπτει το αυτόματα παραγόμενο κείμενο. Το αυτόματα παραγόμενο κείμενο είναι μια έμμεση ιδιότητα της ετικέτας δεδομένων, της ετικέτας μονάδας εμφάνισης του άξονα τιμών, του τίτλου άξονα, του τίτλου γραφήματος, της ετικέτας της γραμμής τάσης. Το αυτόματα παραγόμενο κείμενο μορφοποιείται με την ιδιότητα [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Μόνο-ανάγνωση [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Καθορίζει το πλάτος του στοιχείου γραφήματος ως κλασματικό του πλάτους του γραφήματος. Ανάγνωση **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Καθορίζει τη θέση x (αριστερά) του στοιχείου γραφήματος ως κλασματικό του πλάτους του γραφήματος. Ανάγνωση **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Καθορίζει το πάνω μέρος του στοιχείου γραφήματος ως κλασματικό του ύψους του γραφήματος. Ανάγνωση **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο είναι μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορικά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Καθορίζει το ύψος του στοιχείου γραφήματος ως κλασματικό του ύψους του γραφήματος. Εγγραφή **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Καθορίζει αν άλλα στοιχεία γραφήματος θα επιτρέπεται να επικαλύπτουν τον τίτλο. Εγγραφή **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Καθορίζει το πλάτος του στοιχείου γραφήματος ως κλασματικό του πλάτους του γραφήματος. Εγγραφή **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Καθορίζει τη θέση x (αριστερά) του στοιχείου γραφήματος ως κλασματικό του πλάτους του γραφήματος. Εγγραφή **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Καθορίζει το πάνω μέρος του στοιχείου γραφήματος ως κλασματικό του ύψους του γραφήματος. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ILayoutable](../ilayoutable/)
* Κλάση [IOverridableText](../ioverridabletext/)
* Κλάση [IActualLayout](../iactuallayout/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)