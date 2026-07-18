---
title: IDataLabel
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά ετικέτες σειράς.
type: docs
weight: 937
url: /el/aspose.slides.charts/idatalabel/
---
## IDataLabel κλάση


Represents a series labels.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμα και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμα και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Καθορίζει το πραγματικό επάνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Αποκτά το επάνω μέρος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Μόνο-ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το διάγραμμα. Μόνο-ανάγνωση [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Επιστρέφει τη μορφοποίηση της ετικέτας δεδομένων. Μόνο-ανάγνωση [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Καθορίζει το ύψος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Το false σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*- (ShowValue, ...) είναι false). Μόνο-ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο-ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Αποκτά το δεξιό άκρο του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Μόνο-ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο-ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Επιστρέφει τη μορφοποίηση κειμένου διαγράμματος. Μόνο-ανάγνωση [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Αν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα παραγόμενο κείμενο. Το αυτόματα παραγόμενο κείμενο είναι μια έμμεση ιδιότητα της ετικέτας δεδομένων, της ετικέτας μονάδας εμφάνισης του άξονα τιμών, του τίτλου του άξονα, του τίτλου του διαγράμματος, της ετικέτας της γραμμής τάσης. Το αυτόματα παραγόμενο κείμενο μορφοποιείται με την ιδιότητα [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Μόνο-ανάγνωση [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Αποκτά το κελί δεδομένων του φύλλου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat::get(set)_ShowLabelValueFromCell είναι true. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Καθορίζει το πλάτος του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Καθορίζει την θέση x (αριστερά) του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Καθορίζει το επάνω μέρος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων [DataLabelFormat](../datalabelformat/) ή της τιμής TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που είναι συνδεδεμένη με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | Κάνει την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*- (ShowValue, ...) σε κατάσταση false. Το IsVisible θα είναι false μετά από αυτό. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικός του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή υποτύπων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή υποτύπων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Καθορίζει το ύψος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Ορίζει το κελί δεδομένων του φύλλου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat::get(set)_ShowLabelValueFromCell είναι true. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Καθορίζει το πλάτος του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Καθορίζει την θέση x (αριστερά) του στοιχείου διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Καθορίζει το επάνω μέρος του στοιχείου διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλείστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ILayoutable](../ilayoutable/)
* Κλάση [IOverridableText](../ioverridabletext/)
* Κλάση [IActualLayout](../iactuallayout/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)