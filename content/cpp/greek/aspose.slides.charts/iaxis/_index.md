---
title: IAxis
second_title: Aspose.Slides για C++ API Αναφορά
description: Συγκραίνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 534
url: /el/aspose.slides.charts/iaxis/
---
## IAxis κλάση

Encapsulates the object that represents a chart's axis.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο σε καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο σε καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο [IChart::ValidateChartLayout](../ichart/validatechartlayout/) προηγουμένως για να λάβετε την πραγματική τιμή. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (δισοποίηση). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Αναπαριστά εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. Ανάγνωση [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType έχει τιμή [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το διάγραμμα. Μόνο ανάγνωση [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Αναπαριστά το CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. Ανάγνωση [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Αναπαριστά τη μορφή του άξονα. Μόνο ανάγνωση [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Δείχνει αν η κύρια μονάδα του άξονα ανατίθεται αυτόματα. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Δείχνει αν η μέγιστη τιμή ανατίθεται αυτόματα. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Δείχνει αν η δευτερεύουσα μονάδα του άξονα ανατίθεται αυτόματα. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Δείχνει αν η ελάχιστη τιμή ανατίθεται αυτόματα. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Καθορίζει αυτόματη τιμή overflow bin. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Καθορίζει αυτόματη τιμή διαχώρισματος ετικετών σημάνσεων. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Καθορίζει αυτόματη τιμή διαχώρισματος σημάνσεων. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Καθορίζει αυτόματη τιμή underflow bin. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Δείχνει αν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. Ανάγνωση **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Καθορίζει αν εφαρμόζεται overflow bin. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bin. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Αναπαριστά αν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Καθορίζει αν εφαρμόζεται underflow bin. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bin. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Αναπαριστά αν ο άξονας είναι ορατός. Ανάγνωση **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Αναπαριστά τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο ανάγνωση [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Αναπαριστά τον τύπο του κύριου σημείου σήμανσης για τον καθορισμένο άξονα. Ανάγνωση [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Αναπαριστά τη μορφή των δευτερευόντων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο ανάγνωση [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Αναπαριστά τον τύπο του δευτερεύοντος σημείου σήμανσης για τον καθορισμένο άξονα. Ανάγνωση [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Αναπαριστά τη ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Αναπαριστά τη συμβολοσειρά μορφής για τις [Axis](../axis/) Labels. Ανάγνωση [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType έχει τιμή [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι ψευδής και η ιδιότητα IsOverflowBin είναι αληθής. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Αναπαριστά τη θέση του άξονα. Ανάγνωση [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Αναπαριστά αν εμφανίζονται οι κύριες γραμμές πλέγματος. Μόνο ανάγνωση **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Αναπαριστά αν εμφανίζονται οι δευτερεύουσες γραμμές πλέγματος. Μόνο ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Επιστρέφει τη μορφή κειμένου διαγράμματος. Μόνο ανάγνωση [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Αναπαριστά τη θέση των ετικετών σημάνσεων στον καθορισμένο άξονα. Ανάγνωση [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Αναπαριστά τη γωνία περιστροφής των ετικετών σήμανσης. Ανάγνωση **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Καθορίζει πόσες ετικέτες σημάνσεων θα παραλειφθούν μεταξύ δύο σχεδιασμένων ετικετών. Ανάγνωση **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Καθορίζει πόσες σημάνσεις θα παραλειφθούν πριν σχεδιαστεί η επόμενη. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Αποκτά τον τίτλο του άξονα. Μόνο ανάγνωση [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Καθορίζει προσαρμογμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι ψευδής και η ιδιότητα IsUnderflowBin είναι αληθής. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογίας της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Κλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογίας της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενα τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη σύγκριση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (δισοποίηση). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Αναπαριστά εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας, και δεν ισχύει για 3-Δ διαγράμματα. Εγγραφή **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. Εγγραφή [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType έχει τιμή [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Καθορίζει τον τύπο του άξονα κατηγορίας. Εγγραφή [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Εγγραφή **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Αναπαριστά το CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. Εγγραφή [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Εγγραφή [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Δείχνει αν η κύρια μονάδα του άξονα ανατίθεται αυτόματα. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Δείχνει αν η μέγιστη τιμή ανατίθεται αυτόματα. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Δείχνει αν η δευτερεύουσα μονάδα του άξονα ανατίθεται αυτόματα. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Δείχνει αν η ελάχιστη τιμή ανατίθεται αυτόματα. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Καθορίζει αυτόματη τιμή overflow bin. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Καθορίζει αυτόματη τιμή διαχώρισματος ετικετών σημάνσεων. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Καθορίζει αυτόματη τιμή διαχώρισματος σημάνσεων. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Εγγραφή **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Καθορίζει αυτόματη τιμή underflow bin. Εάν είναι ψευδές: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Εγγραφή **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Δείχνει αν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. Εγγραφή **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Καθορίζει αν εφαρμόζεται overflow bin. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bin. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Αναπαριστά αν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Εγγραφή **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Καθορίζει αν εφαρμόζεται underflow bin. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bin. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Αναπαριστά αν ο άξονας είναι ορατός. Εγγραφή **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Εγγραφή **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Εγγραφή **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Αναπαριστά τον τύπο του κύριου σημείου σήμανσης για τον καθορισμένο άξονα. Εγγραφή [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Εγγραφή **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Εγγραφή [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. Εγγραφή **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Αναπαριστά τον τύπο του δευτερεύοντος σημείου σήμανσης για τον καθορισμένο άξονα. Εγγραφή [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Εγγραφή **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Εγγραφή [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Αναπαριστά τη ελάχιστη τιμή στον άξονα τιμών. Εγγραφή **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Αναπαριστά τη συμβολοσειρά μορφής για τις [Axis](../axis/) Labels. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType έχει τιμή [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι ψευδής και η ιδιότητα IsOverflowBin είναι αληθής. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Αναπαριστά τη θέση του άξονα. Εγγραφή [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Αναπαριστά τη θέση των ετικετών σημάνσεων στον καθορισμένο άξονα. Εγγραφή [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Αναπαριστά τη γωνία περιστροφής των ετικετών σήμανσης. Εγγραφή **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Καθορίζει πόσες ετικέτες σημάνσεων θα παραλειφθούν μεταξύ των σχεδιασμένων ετικετών. Εγγραφή **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Καθορίζει πόσες σημάνσεις θα παραλειφθούν πριν σχεδιαστεί η επόμενη. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Εγγραφή **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Καθορίζει προσαρμογμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι ψευδής και η ιδιότητα IsUnderflowBin είναι αληθής. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Ορίζει την ιδιότητα IAxis::get(set)_CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογίας της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Καθαρίζει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IFormattedTextContainer](../iformattedtextcontainer/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)