---
title: Axis
second_title: Aspose.Sildes για .NET API Αναφορά
description: Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 1160
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
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα της κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα της δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/εγγραφή Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Καθορίζει τη μικρότερη μονάδα χρόνου που αντιπροσωπεύεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Καθορίζει το πλάτος του κάδου όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Επιστρέφει το γονικό διάγραμμα. Μόνο ανάγνωση [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Αντιπροσωπεύει το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας τον διασχίζει. Ανάγνωση/εγγραφή [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Αντιπροσωπεύει τη μορφοποίηση του άξονα. Μόνο ανάγνωση [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Δείχνει εάν η κύρια μονάδα του άξονα ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Δείχνει εάν η μέγιστη τιμή ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Δείχνει εάν η δευτερεύουσα μονάδα του άξονα ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Δείχνει εάν η ελάχιστη τιμή ανατίθεται αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή υπερπλήρωσης κάδου. Εάν ψευδές: χρησιμοποίηστε την ιδιότητα OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημαδιών. Εάν ψευδές: χρησιμοποίηστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης σήμανσης. Εάν ψευδές: χρησιμοποίητε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή υπογέμισης κάδου. Εάν ψευδές: χρησιμοποίητε την ιδιότητα UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Δείχνει εάν η μορφή συνδέεται με δεδομένα πηγής. Ανάγνωση/εγγραφή Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται υπερπλήρωση κάδου. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του κάδου υπερπλήρωσης. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τέλος προς την αρχή. Ανάγνωση/εγγραφή Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται υπογέμιση κάδου. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του κάδου υπογέμισης. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Αντιπροσωπεύει τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε έναν άξονα διαγράμματος. Μόνο ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο του κύριου σήματος σήμανσης για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των δευτερευόντων γραμμών πλέγματος σε έναν άξονα διαγράμματος. Μόνο ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο του δευτεροβάθμιου σήματος σήμανσης για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες άξονα. Ανάγνωση/εγγραφή String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Καθορίζει τον αριθμό των κάδων όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή υπερπλήρωσης κάδου. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι ψευδής και η ιδιότητα IsOverflowBin είναι αληθής. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Αντιπροσωπεύει τη θέση του άξονα. Ανάγνωση/εγγραφή [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Για να κρύψετε την κύρια γραμμή πλέγματος, ορίστε το MajorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο ανάγνωση Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Για να κρύψετε τη δευτερεύουσα γραμμή πλέγματος, ορίστε το MinorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο ανάγνωση Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Αντιπροσωπεύει τη μορφοποίηση του κειμένου. Μόνο ανάγνωση [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Αντιπροσωπεύει τη θέση των ετικετών σήμαδιών στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σήμαδιών. Ανάγνωση/εγγραφή Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Καθορίζει πόσες ετικέτες σήμαδιών να παραλειφθούν μεταξύ των σχεδιασμένων ετικετών. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Καθορίζει πόσες σημαδοφόρες γραμμές να παραληφθούν πριν σχεδιαστεί η επόμενη. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Λαμβάνει τον τίτλο του άξονα. Μόνο ανάγνωση [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή υπογέμισης κάδου. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι ψευδής και η ιδιότητα IsUnderflowBin είναι αληθής. |

## Μεθόδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Ορίζει την ιδιότητα IAxis.CategoryAxisType με μια τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |

### Δείτε επίσης

* κλάση [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* κλάση [AxesManager](../axesmanager)
* διασύνδεση [IAxis](../iaxis)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->