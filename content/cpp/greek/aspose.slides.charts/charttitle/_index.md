---
title: ChartTitle
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει ιδιότητες τίτλου διαγράμματος.
type: docs
weight: 326
url: /el/aspose.slides.charts/charttitle/
---
## ChartTitle κλάση


Αντιπροσωπεύει ιδιότητες τίτλου διαγράμματος.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο \"text\". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πρώτα για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πρώτα για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερή πάνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πρώτα για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερή πάνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πρώτα για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Κάτω. Μόνο για ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Επιστρέφει τα στυλ γεμίσματος, γραμμής, εφέ ενός τίτλου. Μόνο για ανάγνωση [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Επιστρέφει το ύψος ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Καθορίζει εάν άλλα στοιχεία διαγράμματος θα επιτρέπεται να επικαλύπτουν τον τίτλο. Ανάγνωση **bool**. |
| **float** [get_Right](./get_right/)() override | Δεξιά. Μόνο για ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Επιστρέφει τη μορφοποίηση κειμένου. Μόνο για ανάγνωση [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου παρακάμπτει το αυτόματα παραγόμενο κείμενο. Το αυτόματα παραγόμενο κείμενο είναι μια έμμεση ιδιότητα της ετικέτας δεδομένων, της ετικέτας μονάδας απεικόνισης του άξονα τιμών, του τίτλου άξονα, του τίτλου διαγράμματος, της ετικέτας της γραμμής τάσης. Το αυτόματα παραγόμενο κείμενο μορφοποιείται με την ιδιότητα [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Μόνο για ανάγνωση [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Επιστρέφει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| **float** [get_X](./get_x/)() override | Επιστρέφει τη συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| **float** [get_Y](./get_y/)() override | Επιστρέφει τη συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement κλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_Height](./set_height/)(**float**) override | Ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Καθορίζει εάν άλλα στοιχεία διαγράμματος θα επιτρέπεται να επικαλύπτονται τον τίτλο. Εγγραφή **bool**. |
| void [set_Width](./set_width/)(**float**) override | Ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| void [set_X](./set_x/)(**float**) override | Ορίζει τη συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| void [set_Y](./set_y/)(**float**) override | Ορίζει τη συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement ξεκλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [IChartTitle](../icharttitle/)
* Κλάση [IDOMObject](../../aspose.slides/idomobject/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)