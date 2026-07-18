---
title: ICell
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αντιπροσωπεύει ένα κελί σε έναν πίνακα.
type: docs
weight: 1639
url: /el/aspose.slides/icell/
---
## ICell κλάση

Αντιπροσωπεύει ένα κελί σε έναν πίνακα.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την [Object.Equals](../../system/object/equals/) σημασιολογία της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Διαβάστε **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Επιστρέφει το αντικείμενο [CellFormat](../cellformat/) που περιέχει τις ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο ανάγνωση [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Επιστρέφει τον αριθμό των στηλών του πλέγματος του γονικού πίνακα που πρέπει να καλυφθούν από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να έχουν την εμφάνιση συγχώνευσης, καθώς καλύπτουν τις κάθετες οριοθεσίες άλλων κελιών στον πίνακα. Μόνο ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Λαμβάνει την πρώτη στήλη του κελιού. Μόνο ανάγνωση [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Επιστρέφει το ευρετήριο της πρώτης στήλης που καλύπτεται από το κελί. Μόνο ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Λαμβάνει την πρώτη γραμμή του κελιού. Μόνο ανάγνωση [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Επιστρέφει το ευρετήριο της πρώτης γραμμής που καλύπτεται από το κελί. Μόνο ανάγνωση **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Επιστρέφει το ύψος του κελιού. Μόνο ανάγνωση **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Επιστρέφει true εάν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, false διαφορετικά. Μόνο ανάγνωση **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Επιστρέφει το κάτω περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Επιστρέφει το αριστερό περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Επιστρέφει το δεξί περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Επιστρέφει το άνω περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των γραμμών που καλύπτονται από το κελί. Μόνο ανάγνωση **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Επιστρέφει την απόσταση από την αριστερή πλευρά ενός πίνακα μέχρι την αριστερή πλευρά ενός κελιού. Μόνο ανάγνωση **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Επιστρέφει την απόσταση από την άνω πλευρά ενός πίνακα μέχρι την άνω πλευρά ενός κελιού. Μόνο ανάγνωση **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο ανάγνωση [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Επιστρέφει τον αριθμό των γραμμών που καλύπτει ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά για τον ορισμό του αρχικού κελιού μιας οριζόντιας συγχώνευσης. Μόνο ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο ανάγνωση [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Επιστρέφει το γονικό αντικείμενο [Table](../table/) για ένα κελί. Μόνο ανάγνωση [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Επιστρέφει τον τύπο αγκύρωσης κειμένου. Διαβάστε [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Επιστρέφει το πλαίσιο κειμένου ενός κελιού. Μόνο ανάγνωση [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Επιστρέφει τον τύπο κάθετου κειμένου. Διαβάστε [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Επιστρέφει το πλάτος του κελιού. Μόνο ανάγνωση **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία του κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Γράψτε **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ορίζει το κάτω περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ορίζει το αριστερό περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ορίζει το δεξί περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ορίζει το άνω περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Ορίζει τον τύπο αγκύρωσης κειμένου. Γράψτε [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Ορίζει τον τύπο κάθετου κειμένου. Γράψτε [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Διαιρεί το κελί σε δύο κελιά με βάση το ευρετήριο της στήλης. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Διαιρεί το κελί κατά ύψος. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Διαιρεί το κελί σε δύο κελιά με βάση το ευρετήριο της γραμμής. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Διαιρεί το κελί κατά πλάτος. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του statement lock() της C#. Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ISlideComponent](../islidecomponent/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)