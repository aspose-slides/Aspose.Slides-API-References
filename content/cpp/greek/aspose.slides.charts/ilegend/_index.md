---
title: ILegend
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναπαριστά τις ιδιότητες του υπομνήματος του διαγράμματος.
type: docs
weight: 1080
url: /el/aspose.slides.charts/ilegend/
---
## ILegend κλάση

Αντιπροσωπεύει τις ιδιότητες του υπομνήματος του διαγράμματος.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Καθορίζει το πραγματικό άνω μέρος του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Κλήστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Λαμβάνει το άνω μέρος του στοιχείου του διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Μόνο-ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το διάγραμμα. Μόνο-ανάγνωση [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Λαμβάνει τις καταχωρήσεις του υπομνήματος. Μόνο-ανάγνωση [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Λαμβάνει τις ιδιότητες της καταχώρησης υπομνήματος που αντιστοιχεί στο σημείο δεδομένων στο διάγραμμα στο καθορισμένο δείκτη. Για τύπους διαγράμματος: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, το σημείο δεδομένων λαμβάνεται από την πρώτη σειρά. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Επιστρέφει τη μορφή ενός υπομνήματος. Μόνο-ανάγνωση [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Καθορίζει το ύψος του στοιχείου του διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Καθορίζει αν άλλα στοιχεία του διαγράμματος πρέπει να επιτρέπεται να επικαλύπτουν το υπόμνημα. Ανάγνωση **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Καθορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. Οι τιμές διαφορετικές από NaN των ιδιοτήτων X, Y, Width, Heigt αντικαθιστούν την επίδραση αυτής της ιδιότητας. Ανάγνωση [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο-ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Λαμβάνει το δεξιό μέρος του στοιχείου του διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Μόνο-ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο-ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Επιστρέφει τη μορφή κειμένου του διαγράμματος. Μόνο-ανάγνωση [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Καθορίζει το πλάτος του στοιχείου του διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Καθορίζει τη θέση x (αριστερά) του στοιχείου του διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Καθορίζει το άνω μέρος του στοιχείου του διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Καθορίζει το ύψος του στοιχείου του διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Καθορίζει αν άλλα στοιχεία του διαγράμματος πρέπει να επιτρέπεται να επικαλύπτουν το υπόμνημα. Εγγραφή **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Καθορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. Οι τιμές διαφορετικές από NaN των ιδιοτήτων X, Y, Width, Heigt αντικαθιστούν την επίδραση αυτής της ιδιότητας. Εγγραφή [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Καθορίζει το πλάτος του στοιχείου του διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Καθορίζει τη θέση x (αριστερά) του στοιχείου του διαγράμματος ως κλάσμα του πλάτους του διαγράμματος. Εγγραφή **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Καθορίζει το άνω μέρος του στοιχείου του διαγράμματος ως κλάσμα του ύψους του διαγράμματος. Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθεία· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ILayoutable](../ilayoutable/)
* Κλάση [IFormattedTextContainer](../iformattedtextcontainer/)
* Κλάση [IActualLayout](../iactuallayout/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)