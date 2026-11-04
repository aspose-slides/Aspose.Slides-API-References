---
title: IAxis
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καλύπτει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 1720
url: /el/aspose.slides.charts/iaxis/
---
## IAxis διασύνδεση

Καλύπτει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Επιτρέπει την ανάκτηση της βασικής διασύνδεσης IFormattedTextContainer. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/Εγγραφή Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Καθορίζει τη μικρότερη μονάδα χρόνου που αντιπροσωπεύεται στον άξονα ημερομηνίας. Ανάγνωση/Εγγραφή [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Καθορίζει το πλάτος της κούπας όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/Εγγραφή [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/Εγγραφή Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Αντιπροσωπεύει τον CrossType στον καθορισμένο άξονα όπου διασχίζεται από τον άλλο άξονα. Ανάγνωση/Εγγραφή [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/Εγγραφή [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Αντιπροσωπεύει τη μορφή του άξονα. Μόνο για ανάγνωση [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Υποδεικνύει εάν η κύρια μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Υποδεικνύει εάν η μέγιστη τιμή εκχωρείται αυτόματα. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Υποδεικνύει εάν η ελάχιστη τιμή εκχωρείται αυτόματα. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή της κούπας υπερχείλισης. Αν ψευδές: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημείων. Αν ψευδές: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης σημείων σήμανσης. Αν ψευδές: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/Εγγραφή Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή της κούπας υπορροής. Αν ψευδές: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/Εγγραφή Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Υποδεικνύει εάν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. Ανάγνωση/Εγγραφή Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται κούπα υπερχείλισης. Χρησιμοποιήστε τα IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή της κούπας υπερχείλισης. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/Εγγραφή Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Καθορίζει εάν εφαρμόζεται κούπα υπορροής. Χρησιμοποιήστε τα IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή της κούπας υπορροής. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. Ανάγνωση/Εγγραφή Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/Εγγραφή UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Αντιπροσωπεύει τη λογάριθμη βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/Εγγραφή Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε έναν άξονα διαγράμματος. Μόνο για ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο του κύριου σημείου σήμανσης για τον καθορισμένο άξονα. Ανάγνωση/Εγγραφή [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/Εγγραφή Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/Εγγραφή [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/Εγγραφή Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των δευτερευουσών γραμμών πλέγματος σε έναν άξονα διαγράμματος. Μόνο για ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο του δευτερεύοντος σημείου σήμανσης για τον καθορισμένο άξονα. Ανάγνωση/Εγγραφή [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/Εγγραφή Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/Εγγραφή [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/Εγγραφή Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις Ετικέτες Άξονα. Ανάγνωση/Εγγραφή String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Καθορίζει τον αριθμό των κούπων όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Καθορίζει την προσαρμοσμένη τιμή της κούπας υπερχείλισης. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin είναι true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Αντιπροσωπεύει τη θέση του άξονα. Ανάγνωση/Εγγραφή [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Αντιπροσωπεύει εάν εμφανίζονται οι κύριες γραμμές πλέγματος. Μόνο για ανάγνωση Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Αντιπροσωπεύει εάν εμφανίζονται οι δευτερεύουσες γραμμές πλέγματος. Μόνο για ανάγνωση Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Αντιπροσωπεύει τη θέση των ετικετών σημείων σήμανσης στον καθορισμένο άξονα. Ανάγνωση/Εγγραφή [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σημείων σήμανσης. Ανάγνωση/Εγγραφή Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Καθορίζει πόσες ετικέτες σημείων σήμανσης να παραλείπονται μεταξύ των ετικετών που εμφανίζονται. Ανάγνωση/Εγγραφή UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Καθορίζει πόσα σημεία σήμανσης θα παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/Εγγραφή UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Ανακτά τον τίτλο του άξονα. Μόνο για ανάγνωση [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Καθορίζει την προσαρμοσμένη τιμή της κούπας υπορροής. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin είναι true. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Ορίζει την ιδιότητα IAxis.CategoryAxisType με μια τιμή που καθορίζεται αυτόματα με βάση τα δεδομένα του άξονα. |

### Δείτε επίσης

* διασύνδεση [IFormattedTextContainer](../iformattedtextcontainer)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->