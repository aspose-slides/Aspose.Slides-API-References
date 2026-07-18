---
title: LineFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά τη μορφή μιας γραμμής.
type: docs
weight: 4382
url: /el/aspose.slides/lineformat/
---
## LineFormat κλάση

Αναπαριστά τη μορφή μιας γραμμής.

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | Καθορίζει εάν τα δύο [LineFormat](./) αντικείμενα είναι ίσα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | Επιστρέφει την ευθυγράμμιση της γραμμής. Διαβάστε [LineAlignment](../linealignment/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | Επιστρέφει το μήκος της άκρης βέλους στην αρχή μιας γραμμής. Διαβάστε [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | Επιστρέφει το στυλ της άκρης βέλους στην αρχή μιας γραμμής. Διαβάστε [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | Επιστρέφει το πλάτος της άκρης βέλους στην αρχή μιας γραμμής. Διαβάστε [LineArrowheadWidth](../linearrowheadwidth/). |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | Επιστρέφει το στυλ άκρου γραμμής. Διαβάστε [LineCapStyle](../linecapstyle/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | Επιστρέφει το προσαρμοσμένο μοτίβο παύλας. Διαβάστε **float**[]. |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | Επιστρέφει το στυλ παύλας της γραμμής. Διαβάστε [LineDashStyle](../linedashstyle/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | Επιστρέφει το μήκος της άκρης βέλους στο τέλος μιας γραμμής. Διαβάστε [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | Επιστρέφει το στυλ της άκρης βέλους στο τέλος μιας γραμμής. Διαβάστε [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | Επιστρέφει το πλάτος της άκρης βέλους στο τέλος μιας γραμμής. Διαβάστε [LineArrowheadWidth](../linearrowheadwidth/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | Επιστρέφει τη μορφή γεμίσματος μιας γραμμής. Μόνο για ανάγνωση [ILineFillFormat](../ilinefillformat/). |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | Επιστρέφει true εάν η μορφή της γραμμής δεν είναι ορισμένη (μόλις δημιουργήθηκε, προεπιλογή). Μόνο για ανάγνωση **bool**. |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | Επιστρέφει το στυλ σύνδεσης γραμμών. Διαβάστε [LineJoinStyle](../linejoinstyle/). |
| **float** [get_MiterLimit](./get_miterlimit/)() override | Επιστρέφει το όριο μύτης μιας γραμμής. Διαβάστε **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονείο [IPresentationComponent](../ipresentationcomponent/). Μόνο για ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | Επιστρέφει τη μορφή σκίτσου μιας γραμμής. Μόνο για ανάγνωση [ILineFillFormat](../ilinefillformat/). |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | Επιστρέφει το στυλ της γραμμής. Διαβάστε [LineStyle](../linestyle/). |
| **double** [get_Width](./get_width/)() override | Επιστρέφει το πλάτος μιας γραμμής. Διαβάστε **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γραμμής με την εφαρμογή κληρονομικότητας. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση τύπου όπως περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) φρουρού. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά τη συγκεκριμένη τιμή. |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | Ορίζει την ευθυγράμμιση της γραμμής. Γράψτε [LineAlignment](../linealignment/). |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Ορίζει το μήκος της άκρης βέλους στην αρχή μιας γραμμής. Γράψτε [LineArrowheadLength](../linearrowheadlength/). |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Ορίζει το στυλ της άκρης βέλους στην αρχή μιας γραμμής. Γράψτε [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Ορίζει το πλάτος της άκρης βέλους στην αρχή μιας γραμμής. Γράψτε [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | Ορίζει το στυλ άκρου γραμμής. Γράψτε [LineCapStyle](../linecapstyle/). |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Ορίζει το προσαρμοσμένο μοτίβο παύλας. Γράψτε **float**[]. |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | Ορίζει το στυλ παύλας της γραμμής. Γράψτε [LineDashStyle](../linedashstyle/). |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Ορίζει το μήκος της άκρης βέλους στο τέλος μιας γραμμής. Γράψτε [LineArrowheadLength](../linearrowheadlength/). |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Ορίζει το στυλ της άκρης βέλους στο τέλος μιας γραμμής. Γράψτε [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Ορίζει το πλάτος της άκρης βέλους στο τέλος μιας γραμμής. Γράψτε [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | Ορίζει το στυλ σύνδεσης γραμμών. Γράψτε [LineJoinStyle](../linejoinstyle/). |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | Ορίζει το όριο μύτης μιας γραμμής. Γράψτε **float**. |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | Ορίζει το στυλ της γραμμής. Γράψτε [LineStyle](../linestyle/). |
| void [set_Width](./set_width/)(**double**) override | Ορίζει το πλάτος μιας γραμμής. Γράψτε **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) φρουρού. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [ILineFormat](../ilineformat/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)