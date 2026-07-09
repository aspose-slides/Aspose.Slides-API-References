---
title: IAxis
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αποτυπώνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 1710
url: /el/aspose.slides.charts/iaxis/
---
## IAxis διασύνδεση

Αποτυπώνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Καθορίζει την πραγματική μεγέθυνση κύριου μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα κύριου μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Καθορίζει την πραγματική μικρή μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα μικρής μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Επιτρέπει την απόκτηση της βάσης διασύνδεσης IFormattedTextContainer. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Αναγνώσιμη/εγγράψιμη Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. Αναγνώσιμη/εγγράψιμη [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Καθορίζει το πλάτος της κάδου όταν η τιμή της ιδιότητας AggregationType είναι AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Καθορίζει τον τύπο του άξονα κατηγορίας. Αναγνώσιμη/εγγράψιμη [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονα τον διασχίζει. Αναγνώσιμη/εγγράψιμη Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Αντιπροσωπεύει τον CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. Αναγνώσιμη/εγγράψιμη [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Αναγνώσιμη/εγγράψιμη [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Αντιπροσωπεύει τη μορφή του άξονα. Μόνο για ανάγνωση [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Υποδεικνύει εάν η κύρια μονάδα του άξονα ανατίθεται αυτόματα. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Υποδεικνύει εάν η μέγιστη τιμή ανατίθεται αυτόματα. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Υποδεικνύει εάν η μικρή μονάδα του άξονα ανατίθεται αυτόματα. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Υποδεικνύει εάν η ελάχιστη τιμή ανατίθεται αυτόματα. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή overflow bin. Αν false: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημάνων. Αν false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης σημείων. Αν false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή underflow bin. Αν false: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Υποδεικνύει εάν η μορφή είναι συνδεδεμένα δεδομένα πηγής. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται overflow bin. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bin. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Αναγνώσιμη/εγγράψιμη Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται underflow bin. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bin. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. Αναγνώσιμη/εγγράψιμη Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Αναγνώσιμη/εγγράψιμη UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Αντιπροσωπεύει τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Αναγνώσιμη/εγγράψιμη Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο της κύριας σημάνσης για τον καθορισμένο άξονα. Αναγνώσιμη/εγγράψιμη [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Αναγνώσιμη/εγγράψιμη Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Αντιπροσωπεύει τη κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Αναγνώσιμη/εγγράψιμη [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Αναγνώσιμη/εγγράψιμη Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των μικρών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο της μικρής σημάνσης για τον καθορισμένο άξονα. Αναγνώσιμη/εγγράψιμη [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Αντιπροσωπεύει τις μικρές μονάδες για τον άξονα ημερομηνίας ή τιμής. Αναγνώσιμη/εγγράψιμη Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Αντιπροσωπεύει τη κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Αναγνώσιμη/εγγράψιμη [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. Αναγνώσιμη/εγγράψιμη Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες άξονα. Αναγνώσιμη/εγγράψιμη String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Καθορίζει τον αριθμό των κάδων όταν η τιμή της ιδιότητας AggregationType είναι AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι false και η ιδιότητα IsOverflowBin είναι true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Αντιπροσωπεύει τη θέση του άξονα. Αναγνώσιμη/εγγράψιμη [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Αντιπροσωπεύει εάν εμφανίζονται οι κύριες γραμμές πλέγματος. Μόνο για ανάγνωση Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Αντιπροσωπεύει εάν εμφανίζονται οι μικρές γραμμές πλέγματος. Μόνο για ανάγνωση Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Αντιπροσωπεύει τη θέση των ετικετών των σημείων σήμανσης στον καθορισμένο άξονα. Αναγνώσιμη/εγγράψιμη [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σημείων. Αναγνώσιμη/εγγράψιμη Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Καθορίζει πόσες ετικέτες σημείων να παραλειφθούν μεταξύ των σχεδιαζόμενων ετικετών. Αναγνώσιμη/εγγράψιμη UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Καθορίζει πόσες σημάνσεις να παραλειφθούν πριν σχεδιαστεί η επόμενη. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Αναγνώσιμη/εγγράψιμη UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Αποκτά τον τίτλο του άξονα. Μόνο για ανάγνωση [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι false και η ιδιότητα IsUnderflowBin είναι true. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Ορίζει την ιδιότητα IAxis.CategoryAxisType με μια τιμή που προσδιορίζεται αυτόματα βάσει των δεδομένων του άξονα. |

### Δείτε επίσης

* διασύνδεση [IFormattedTextContainer](../iformattedtextcontainer)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->