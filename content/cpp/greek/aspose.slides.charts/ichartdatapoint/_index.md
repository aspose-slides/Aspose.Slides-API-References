---
title: IChartDataPoint
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει σημείο δεδομένων σειράς.
type: docs
weight: 677
url: /el/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint κλάση


Αντιπροσωπεύει σημείο δεδομένων σειράς.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας το C# [Object.Equals](../../system/object/equals/) σημασιολογία. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Κλήση μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Κλήση μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Καθορίζει την πραγματική τοποθεσία x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με το αριστερό άνω άκρο του διαγράμματος. Κλήση μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Καθορίζει το πραγματικό άνω μέρος του στοιχείου του διαγράμματος σε σχέση με το αριστερό άνω άκρο του διαγράμματος. Κλήση μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | Επιστρέφει το μέγεθος φυσαλίδας του σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων διαγράμματος. Χρησιμοποιείται με χάρτες Map. Μόνο ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | Επιστρέφει ένα επίπεδο σημείου δεδομένων στον καθορισμένο δείκτη. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση επιπέδων σημείου δεδομένων αρχίζει από το μηδέν. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | Επιστρέφει τον container των επιπέδων σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση επιπέδων σημείου δεδομένων αρχίζει από το μηδέν. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | Αναπαριστά τις τιμές γραμμών σφάλματος σειράς στην περίπτωση τύπου προσαρμοσμένης τιμής. Μόνο ανάγνωση [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων πρέπει να μετακινηθεί από το κέντρο της πίτας. Ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | Καθορίζει σε ποια συλλογή παιδιών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. Ανάγνωση **uint32_t**. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση **bool**. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | Αναπαριστά την ετικέτα του σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | Καθορίζει έναν δείκτη δεδομένων. Μόνο ανάγνωση [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Ιδιότητες της αντίστοιχης καταχώρισης υπομνήματος στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Μόνο ανάγνωση [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για τύπο σειράς Waterfall. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων διαγράμματος. Χρησιμοποιείται με διαγράμματα Treemap και Sunburst. Μόνο ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | Επιστρέφει την τιμή του σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | Επιστρέφει την τιμή x του σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | Επιστρέφει την τιμή y του σημείου δεδομένων διαγράμματος. Μόνο ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, δείκτη σημείου δεδομένων, της ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType ισούται με NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Παρόμοια με τη μέθοδο C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει τον κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Παρόμοιο με την κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Παρόμοιο με τον τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Παρόμοιο με τη μέθοδο C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| virtual void [Remove](./remove/)() | Απομακρύνει το DataPoint από τη σειρά του διαγράμματος. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων πρέπει να μετακινηθεί από το κέντρο της πίτας. Εγγραφή **int32_t**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Αναπαριστά τις ιδιότητες μορφοποίησης. Εγγραφή [IFormat](../iformat/). |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Εγγραφή **bool**. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3Δ. Εγγραφή **bool**. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για τύπο σειράς Waterfall. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Παρόμοιο με τη μέθοδο C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [IActualLayout](../iactuallayout/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)