---
title: Axis
second_title: Aspose.Sildes για .NET API Αναφορά
description: Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 1180
url: /el/aspose.slides.charts/axis/
---
## Axis κλάση

Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Καθορίζει τη πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Αναπαριστά εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/εγγραφή Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Καθορίζει τη μικρότερη μονάδα χρόνου που αντιπροσωπεύεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Καθορίζει το πλάτος ομάδας όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Επιστρέφει το γονικό διάγραμμα. Μόνο ανάγνωση [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διέρχεται. Ανάγνωση/εγγραφή Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Αναπαριστά τον CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. Ανάγνωση/εγγραφή [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Αναπαριστά τη μορφή του άξονα. Μόνο ανάγνωση [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Δηλώνει εάν η κύρια μονάδα του άξονα ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Δηλώνει εάν η μέγιστη τιμή ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Δηλώνει εάν η δευτερεύουσα μονάδα του άξονα ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Δηλώνει εάν η ελάχιστη τιμή ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή του overflow bin. Εάν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης ετικετών χρονοσήμαδιων. Εάν είναι false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης σημείων χρονοσήμαδιων. Εάν είναι false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή του underflow bin. Εάν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Δηλώνει εάν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. Ανάγνωση/εγγραφή Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται overflow bin. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για την προσαρμογή της τιμής του overflow bin. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Αναπαριστά εάν το MS PowerPoint σχεδιάζει σημεία δεδομένων από το τέλος προς την αρχή. Ανάγνωση/εγγραφή Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται underflow bin. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για την προσαρμογή της τιμής του underflow bin. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Αναπαριστά εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Αναπαριστά τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Αναπαριστά τον τύπο του κύριου σημείου χρονοσήμανσης για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Αναπαριστά τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Αναπαριστά τον τύπο των δευτερευουσών σημείων χρονοσήμανσης για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Αναπαριστά τη ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Αναπαριστά τη συμβολοσειρά μορφής για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin είναι true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Για να κρύψετε την κύρια γραμμή πλέγματος ορίστε το MajorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο ανάγνωση Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Για να κρύψετε την δευτερεύουσα γραμμή πλέγματος ορίστε το MinorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο ανάγνωση Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Αναπαριστά τη μορφή του κειμένου. Μόνο ανάγνωση [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Αναπαριστά τη θέση των ετικετών των σημείων χρονοσήμανσης στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Αναπαριστά τη γωνία περιστροφής των ετικετών χρονοσήμανσης. Ανάγνωση/εγγραφή Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Καθορίζει πόσες ετικέτες χρονοσήμανσης να παραλειφθούν μεταξύ των σχεδιαζόμενων ετικετών. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Καθορίζει πόσα σημεία χρονοσήμανσης πρέπει να παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Αποκτά τον τίτλο του άξονα. Μόνο ανάγνωση [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin είναι true. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Ορίζει την ιδιότητα IAxis.CategoryAxisType με μια τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |

### Δείτε επίσης

* κλάση [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* κλάση [AxesManager](../axesmanager)
* διασύνδεση [IAxis](../iaxis)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->