---
title: Legend
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά τις ιδιότητες του υπομνήματος του διαγράμματος.
type: docs
weight: 1262
url: /el/aspose.slides.charts/legend/
---
## Legend κλάση

Αντιπροσωπεύει τις ιδιότητες του υπομνήματος του διαγράμματος.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος ως προς την αριστερή επάνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου του διαγράμματος ως προς την αριστερή επάνω γωνία του διαγράμματος. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Κάτω. Μόνο-ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Επιστρέφει το διάγραμμα. Μόνο-ανάγνωση [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Λαμβάνει τις καταχωρήσεις του υπομνήματος. Μόνο-ανάγνωση [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Λαμβάνει τις ιδιότητες της καταχώρησης υπομνήματος που αντιστοιχεί σε σημείο δεδομένων στο διάγραμμα στον καθορισμένο δείκτη. Στις περιπτώσεις τύπων διαγράμματος: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, το σημείο δεδομένων λαμβάνεται από την πρώτη σειρά. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Επιστρέφει τη μορφή ενός υπομνήματος. Μόνο-ανάγνωση [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Επιστρέφει το ύψος ενός υπομνήματος ως κλάσμα του ύψους του διαγράμματος. Διαβάστε **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Καθορίζει αν άλλα στοιχεία του διαγράμματος επιτρέπεται να επικαλύπτουν το υπόμνημα. Διαβάστε **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Καθορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. Οι τιμές που δεν είναι NaN των ιδιοτήτων X, Y, Width, Heigt αντικαθιστούν την επίδραση αυτής της ιδιότητας. Διαβάστε [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Δεξιά. Μόνο-ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Μορφή κειμένου. Μόνο-ανάγνωση [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Επιστρέφει το πλάτος ενός υπομνήματος ως κλάσμα του πλάτους του διαγράμματος. Διαβάστε **float**. |
| **float** [get_X](./get_x/)() override | Επιστρέφει το x συντεταγμένο ενός υπομνήματος ως κλάσμα του πλάτους του διαγράμματος. Διαβάστε **float**. |
| **float** [get_Y](./get_y/)() override | Επιστρέφει το y συντεταγμένο ενός υπομνήματος ως κλάσμα του ύψους του διαγράμματος. Διαβάστε **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_Height](./set_height/)(**float**) override | Ορίζει το ύψος ενός υπομνήματος ως κλάσμα του ύψους του διαγράμματος. Εγγράψτε **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Καθορίζει αν άλλα στοιχεία του διαγράμματος επιτρέπεται να επικαλύπτουν το υπόμνημα. Εγγράψτε **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Καθορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. Οι τιμές που δεν είναι NaN των ιδιοτήτων X, Y, Width, Heigt αντικαθιστούν την επίδραση αυτής της ιδιότητας. Εγγράψτε [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Ορίζει το πλάτος ενός υπομνήματος ως κλάσμα του πλάτους του διαγράμματος. Εγγράψτε **float**. |
| void [set_X](./set_x/)(**float**) override | Ορίζει τη συντεταγμένη x ενός υπομνήματος ως κλάσμα του πλάτους του διαγράμματος. Εγγράψτε **float**. |
| void [set_Y](./set_y/)(**float**) override | Ορίζει τη συντεταγμένη y ενός υπομνήματος ως κλάσμα του ύψους του διαγράμματος. Εγγράψτε **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ορίζει το n'th όρισμα προτύπου ως αδύναμε δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [DomObject](../../aspose.slides/domobject/)
* Κλάση [ILegend](../ilegend/)
* Ονομαχώρος [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)