---
title: Axis
second_title: Αναφορά API Aspose.Slides για C++
description: Περιλαμβάνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 14
url: /el/aspose.slides.charts/axis/
---
## Κλάση Axis

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Καθορίζει τη πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Καθορίζει τη πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Αναπαριστά τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Αναπαριστά αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. Ανάγνωση [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Καθορίζει το πλάτος του bin όταν η τιμή της ιδιότητας AggregationType ορίζεται σε [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Αναπαριστά το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. Ανάγνωση [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμής. Ανάγνωση [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Αναπαριστά τη μορφή του άξονα. Μόνο για ανάγνωση [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Καθορίζει αν ένας άξονας έχει ορατό τίτλο. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Δείχνει αν η κύρια μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Δείχνει αν η μέγιστη τιμή εκχωρείται αυτόματα. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Δείχνει αν η δευτερεύουσα μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Δείχνει αν η ελάχιστη τιμή εκχωρείται αυτόματα. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Καθορίζει την αυτόματη τιμή overflow bin. Αν false: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Καθορίζει την αυτόματη τιμή απόστασης ετικετών tick. Αν false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Καθορίζει την αυτόματη τιμή απόστασης σημαδιών tick. Αν false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Καθορίζει την αυτόματη τιμή underflow bin. Αν false: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Αναπαριστά αν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Δείχνει αν η μορφή είναι συνδεδεμένα δεδομένα πηγής. Ανάγνωση **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Καθορίζει αν εφαρμόζεται overflow bin. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή overflow bin. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Αναπαριστά αν το MS PowerPoint σχεδιάζει σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Καθορίζει αν εφαρμόζεται underflow bin. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή underflow bin. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Αναπαριστά αν ο άξονας είναι ορατός. Ανάγνωση **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Αναπαριστά τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Αναπαριστά τον τύπο του κύριου σημείου tick για τον καθορισμένο άξονα. Ανάγνωση [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμής. Ανάγνωση **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Αναπαριστά τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Αναπαριστά τον τύπο του δευτερεύοντος σημείου tick για τον καθορισμένο άξονα. Ανάγνωση [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Αναπαριστά τη ελάχιστη τιμή στον άξονα τιμής. Ανάγνωση **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Αναπαριστά τη συμβολοσειρά μορφής για τις ετικέτες [Axis](./). Ανάγνωση [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType ορίζεται σε [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin ισούται με true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Αναπαριστά τη θέση του άξονα. Ανάγνωση [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Για να κρύψετε την κύρια γραμμή πλέγματος ορίστε [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() σε [FillType::NoFill](../../aspose.slides/filltype/). Μόνο για ανάγνωση **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Για να κρύψετε τη δευτερεύουσα γραμμή πλέγματος ορίστε [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() σε [FillType::NoFill](../../aspose.slides/filltype/). Μόνο για ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Αναπαριστά τη μορφή του κειμένου. Μόνο για ανάγνωση [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Αναπαριστά τη θέση των ετικετών σημείων tick στον καθορισμένο άξονα. Ανάγνωση [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Αναπαριστά τη γωνία περιστροφής των ετικετών tick. Ανάγνωση **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Καθορίζει πόσες ετικέτες tick να παραλειφθούν μεταξύ των ετικετών που σχεδιάζονται. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Καθορίζει πόσα σημεία tick να παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Λαμβάνει τον τίτλο του άξονα. Μόνο για ανάγνωση [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin ισούται με true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αναπαριστά μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογική του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλήση κλειδώματος C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφική κατασκευή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφική κατασκευή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Αναπαριστά τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Αναπαριστά αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Εγγραφή **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. Εγγραφή [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Καθορίζει το πλάτος του bin όταν η τιμή της ιδιότητας AggregationType ορίζεται σε [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Καθορίζει τον τύπο του άξονα κατηγορίας. Εγγραφή [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Εγγραφή **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Αναπαριστά το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. Εγγραφή [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμής. Εγγραφή [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Καθορίζει αν ένας άξονας έχει ορατό τίτλο. Εγγραφή **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Δείχνει αν η κύρια μονάδα του άξονα εκχωρείται αυτόματα. Εγγραφή **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Δείχνει αν η μέγιστη τιμή εκχωρείται αυτόματα. Εγγραφή **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Δείχνει αν η δευτερεύουσα μονάδα του άξονα εκχωρείται αυτόματα. Εγγραφή **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Δείχνει αν η ελάχιστη τιμή εκχωρείται αυτόματα. Εγγραφή **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Καθορίζει την αυτόματη τιμή overflow bin. Αν false: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Καθορίζει την αυτόματη τιμή απόστασης ετικετών tick. Αν false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Εγγραφή **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Καθορίζει την αυτόματη τιμή απόστασης σημαδιών tick. Αν false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Εγγραφή **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Καθορίζει την αυτόματη τιμή underflow bin. Αν false: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Αναπαριστά αν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Εγγραφή **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Δείχνει αν η μορφή είναι συνδεδεμένα δεδομένα πηγής. Εγγραφή **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Καθορίζει αν εφαρμόζεται overflow bin. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή overflow bin. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Αναπαριστά αν το MS PowerPoint σχεδιάζει σημεία δεδομένων από το τελευταίο προς το πρώτο. Εγγραφή **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Καθορίζει αν εφαρμόζεται underflow bin. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή underflow bin. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Αναπαριστά αν ο άξονας είναι ορατός. Εγγραφή **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Εγγραφή **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Εγγραφή **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Αναπαριστά τον τύπο του κύριου σημείου tick για τον καθορισμένο άξονα. Εγγραφή [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Εγγραφή **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Εγγραφή [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμής. Εγγραφή **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Αναπαριστά τον τύπο του δευτερεύοντος σημείου tick για τον καθορισμένο άξονα. Εγγραφή [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Εγγραφή **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Εγγραφή [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Αναπαριστά τη ελάχιστη τιμή στον άξονα τιμής. Εγγραφή **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Αναπαριστά τη συμβολοσειρά μορφής για τις ετικέτες [Axis](./). Εγγραφή [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType ορίζεται σε [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin ισούται με true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Αναπαριστά τη θέση του άξονα. Εγγραφή [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Αναπαριστά τη θέση των ετικετών σημείων tick στον καθορισμένο άξονα. Εγγραφή [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Αναπαριστά τη γωνία περιστροφής των ετικετών tick. Εγγραφή **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Καθορίζει πόσες ετικέτες tick να παραλειφθούν μεταξύ των ετικετών που σχεδιάζονται. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Εγγραφή **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Καθορίζει πόσα σημεία tick να παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Εγγραφή **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin ισούται με true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Ορίζει την ιδιότητα IAxis::get(set)_CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ορίζει το n'th όρισμα προτύπου ως αδυνατό δείκτη (αντί για shared). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε κατάσταση αδυνατότητας. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκευαστικό C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποδεσμευτική κλήση C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [DomObject](../../aspose.slides/domobject/)
* Κλάση [IAxis](../iaxis/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)