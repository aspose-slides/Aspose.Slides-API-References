---
title: Cell
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά ένα κελί ενός πίνακα.
type: docs
weight: 300
url: /el/aspose.slides/cell/
---
## Κλάση Cell

Αναπαριστά ένα κελί ενός πίνακα.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας C# [Object.Equals](../../system/object/equals/) συντακτικό. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει της C# σύγκριση κινητής υποδιαστολής όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει της C# σύγκριση κινητής υποδιαστολής όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Διαβάστε **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Επιστρέφει το αντικείμενο [CellFormat](../cellformat/) που περιέχει τις ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο για ανάγνωση [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Επιστρέφει τον αριθμό των στηλών του πλέγματος του γονικού πίνακα που θα καλύπτονται από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να έχουν την εμφάνιση συγχώνευσης, καθώς καλύπτουν κάθετες όχθες άλλων κελιών στον πίνακα. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Λαμβάνει την πρώτη στήλη του κελιού. Μόνο για ανάγνωση [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Επιστρέφει τον δείκτη της πρώτης στήλης που καλύπτεται από το κελί. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Λαμβάνει την πρώτη σειρά του κελιού. Μόνο για ανάγνωση [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Επιστρέφει τον δείκτη της πρώτης σειράς που καλύπτεται από το κελί. Μόνο για ανάγνωση **int32_t**. |
| **double** [get_Height](./get_height/)() override | Επιστρέφει το ύψος του κελιού. Μόνο για ανάγνωση **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Επιστρέφει true αν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, false διαφορετικά. Μόνο για ανάγνωση **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Επιστρέφει το κάτω περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Επιστρέφει το αριστερό περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Επιστρέφει το δεξιό περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Επιστρέφει το άνω περιθώριο σε ένα [TextFrame](../textframe/). Διαβάστε **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των σειρών που καλύπτονται από το κελί. Μόνο για ανάγνωση **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Επιστρέφει την απόσταση από την αριστερή πλευρά ενός πίνακα μέχρι την αριστερή πλευρά ενός κελιού. Μόνο για ανάγνωση **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Επιστρέφει την απόσταση από την άνω πλευρά ενός πίνακα μέχρι την άνω πλευρά ενός κελιού. Μόνο για ανάγνωση **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Επιστρέφει την γονική παρουσίαση ενός κελιού. Μόνο για ανάγνωση [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Επιστρέφει τον αριθμό των σειρών που καλύπτει ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά για τον καθορισμό του αρχικού κελιού μιας οριζόντιας συγχώνευσης. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Επιστρέφει τη γονική διαφάνεια ενός κελιού. Μόνο για ανάγνωση [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Επιστρέφει το γονικό αντικείμενο [Table](../table/) για ένα κελί. Μόνο για ανάγνωση [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Επιστρέφει τον τύπο άγκυρας κειμένου. Διαβάστε [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Επιστρέφει το πλαίσιο κειμένου ενός κελιού. Μόνο για ανάγνωση [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Επιστρέφει τον τύπο κατακόρυφου κειμένου. Διαβάστε [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Επιστρέφει το πλάτος του κελιού. Μόνο για ανάγνωση **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αποτελεί μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο παρατηρητή [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλά αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλά αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Γράψτε **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Ορίζει το κάτω περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Ορίζει το αριστερό περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Ορίζει το δεξιό περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Ορίζει το άνω περιθώριο σε ένα [TextFrame](../textframe/). Γράψτε **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Ορίζει τον τύπο άγκυρας κειμένου. Γράψτε [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Ορίζει τον τύπο κατακόρυφου κειμένου. Γράψτε [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Διαχωρίζει το κελί σε δύο κελιά βάσει δείκτη στήλης. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Διαχωρίζει το κελί κατά ύψος. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Διαχωρίζει το κελί σε δύο κελιά βάσει δείκτη σειράς. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Διαχωρίζει το κελί κατά πλάτος. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο παρατηρητή [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IDOMObject](../idomobject/)
* Κλάση [ICell](../icell/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)