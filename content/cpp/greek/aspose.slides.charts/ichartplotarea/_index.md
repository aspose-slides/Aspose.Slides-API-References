---
title: IChartPlotArea
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά τις ιδιότητες του τίτλου του διαγράμματος.
type: docs
weight: 794
url: /el/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea κλάση

Αναπαριστά τις ιδιότητες του τίτλου του διαγράμματος.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Καθορίζει τη πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερή πάνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερή πάνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Αποκτά το πάνω μέρος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Μόνο για ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το διάγραμμα. Μόνο για ανάγνωση [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Επιστρέφει τη μορφή μιας περιοχής γραφήματος. Μόνο για ανάγνωση [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Καθορίζει το ύψος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | Εάν η διάταξη της περιοχής γραφήματος ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη της περιοχής γίνεται από το εσωτερικό της (χωρίς τους άξονες και τις ετικέτες αξόνων) ή από το εξωτερικό (συμπεριλαμβανομένων των αξόνων και των ετικετών). Ανάγνωση [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο για ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Αποκτά το δεξι μέρος του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Μόνο για ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο για ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Καθορίζει το πλάτος του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Καθορίζει τη θέση x (αριστερά) του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Καθορίζει το πάνω μέρος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση της συμβολοσειράς και του nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Καθορίζει το ύψος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | Εάν η διάταξη της περιοχής γραφήματος ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη γίνεται από το εσωτερικό (χωρίς άξονες και ετικέτες) ή από το εξωτερικό (συμπεριλαμβανομένων των αξόνων και των ετικετών). Εγγραφή [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Καθορίζει το πλάτος του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Καθορίζει τη θέση x (αριστερά) του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Καθορίζει το πάνω μέρος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως ασθενή δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε ασθενή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή ασθενών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή ασθενών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ILayoutable](../ilayoutable/)
* Κλάση [IActualLayout](../iactuallayout/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)