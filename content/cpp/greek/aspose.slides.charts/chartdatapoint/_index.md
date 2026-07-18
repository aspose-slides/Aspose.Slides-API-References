---
title: ChartDataPoint
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει σημείο δεδομένων σειράς.
type: docs
weight: 144
url: /el/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint κλάση

Represents series data point.

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Κλήση της μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Κλήση της μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Καθορίζει τη πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Κλήση της μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου του διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Κλήση της μεθόδου [IChart::ValidateChartLayout](../ichart/validatechartlayout/) πριν για λήψη πραγματικών τιμών. Ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize. Μόνο για ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με χάρτες Map. Μόνο για ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | Επιστρέφει το επίπεδο σημείου δεδομένων στο συγκεκριμένο δείκτη. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων σημείων δεδομένων είναι μηδενική. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | Επιστρέφει το σύνολο των επιπέδων σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων σημείων δεδομένων είναι μηδενική. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | Αντιπροσωπεύει τις τιμές των σφαλμάτων σειράς σε περίπτωση προσαρμοσμένου τύπου τιμής. Μόνο για ανάγνωση [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| **int32_t** [get_Explosion](./get_explosion/)() override | Καθορίζει το ποσό με το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο της πίτας. Ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Ανάγνωση [IFormat](../iformat/). |
| **uint32_t** [get_Index](./get_index/)() override | Καθορίζει σε ποια συλλογή θυγατρικών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. Ανάγνωση **uint32_t**. |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | Καθορίζει εάν το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. Ανάγνωση **bool**. |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο εφέ 3-Δ. Ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | Ετικέτα. Μόνο για ανάγνωση [IDataLabel](../idatalabel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | Καθορίζει έναν δείκτη δεδομένων. Μόνο για ανάγνωση [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Ιδιότητες της αντίστοιχης καταχώρισης υπόμνησης στην περίπτωση τύπου διαγράμματος από αυτή τη λίστα: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Μόνο για ανάγνωση [ILegendEntryProperties](../ilegendentryproperties/). |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για σειρά τύπου Waterfall. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με χάρτες Treemap και Sunburst. Μόνο για ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | Τιμή. Μόνο για ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | XValue. Μόνο για ανάγνωση [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | YValue. Μόνο για ανάγνωση [IDoubleChartValue](../idoublechartvalue/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | Επιστρέφει ένα αυτόματο χρώμα σημείου δεδομένων βασισμένο στον δείκτη σειράς, δείκτη σημείου δεδομένων, την ιδιότητα ParentSeriesGroup.IsColorVaried και το στυλ του διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType είναι NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση lock() της C# για κλείδωμα. Κλήση απευθείας ή χρήση αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών για υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών για υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| void [Remove](./remove/)() override | Αφαιρεί το DataPoint από τη σειρά του διαγράμματος. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | Καθορίζει το ποσό με το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο της πίτας. Εγγραφή **int32_t**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης. Εγγραφή [IFormat](../iformat/). |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | Καθορίζει εάν το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. Εγγραφή **bool**. |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | Καθορίζει ότι οι φούσκες έχουν εφέ 3-Δ. Εγγραφή **bool**. |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για σειρά τύπου Waterfall. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυνατη δείκτη (αντί για shared). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση lock() της C# για ξεκλείδωμα. Κλήση απευθείας ή χρήση αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυσνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Class [IChartDataPoint](../ichartdatapoint/)
* Class [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)