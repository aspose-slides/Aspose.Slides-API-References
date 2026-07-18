---
title: ChartPlotArea
second_title: Αναφορά API Aspose.Slides για C++
description: Αναπαριστά ορθογώνιο όπου πρέπει να σχεδιαστεί το chart.
type: docs
weight: 248
url: /el/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea κλάση

Αναπαριστά ορθογώνιο όπου πρέπει να σχεδιαστεί το chart.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Καθορίζει το πραγματικό ύψος του στοιχείου chart. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Καθορίζει το πραγματικό πλάτος του στοιχείου chart. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου chart σε σχέση με την αριστερή άνω γωνία του chart. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Καθορίζει το πραγματικό επάνω μέρος του στοιχείου chart σε σχέση με την αριστερή άνω γωνία του chart. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Κάτω. Μόνο για ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Μόνο για ανάγνωση [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Επιστρέφει τη μορφή μιας περιοχής σχεδίασης. Μόνο για ανάγνωση [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Επιστρέφει το ύψος του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του chart (από 0 έως 1). Διαβάζει **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Ορίζει πώς πρέπει να υπολογίζεται η θέση: true – υπολογίζεται αυτόματα· καθορίζεται από τις ιδιότητες X, Y, Width, Height. Μόνο για ανάγνωση **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η περιοχή σχεδίασης θα διαταχθεί με βάση το εσωτερικό της (χωρίς τον άξονα και τις ετικέτες άξονα) ή το εξωτερικό (συμπεριλαμβανομένου του άξονα και των ετικετών άξονα). Διαβάστε [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Δεξιά. Μόνο για ανάγνωση **float**. |
| **float** [get_Width](./get_width/)() override | Επιστρέφει το πλάτος του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του chart (από 0 έως 1). Διαβάζει **float**. |
| **float** [get_X](./get_x/)() override | Επιστρέφει τη συντεταγμένη x του άνω αριστερού γωνιακού σημείου του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του chart (από 0 έως 1). Διαβάζει **float**. |
| **float** [get_Y](./get_y/)() override | Επιστρέφει τη συντεταγμένη y του άνω αριστερού γωνιακού σημείου του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του chart (από 0 έως 1). Διαβάζει **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίσταση του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρός [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση του string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_Height](./set_height/)(**float**) override | Ορίζει το ύψος του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του chart (από 0 έως 1). Εγγραφή **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η περιοχή σχεδίασης θα διαταχθεί με βάση το εσωτερικό της (χωρίς τον άξονα και τις ετικέτες άξονα) ή το εξωτερικό (συμπεριλαμβανομένου του άξονα και των ετικετών άξονα). Εγγραφή [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Ορίζει το πλάτος του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του chart (από 0 έως 1). Εγγραφή **float**. |
| void [set_X](./set_x/)(**float**) override | Ορίζει τη συντεταγμένη x του άνω αριστερού γωνιακού σημείου του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του chart (από 0 έως 1). Εγγραφή **float**. |
| void [set_Y](./set_y/)(**float**) override | Ορίζει τη συντεταγμένη y του άνω αριστερού γωνιακού σημείου του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του chart (από 0 έως 1). Εγγραφή **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ορίζει το n'th όρισμα πρότυπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρός [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [DomObject](../../aspose.slides/domobject/)
* Κλάση [IChartPlotArea](../ichartplotarea/)
* Ονομαχώρος [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)