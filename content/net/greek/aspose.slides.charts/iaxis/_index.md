---
title: IAxis
second_title: Aspose.Sildes για .NET API Αναφορά
description: Περιλαμβάνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
weight: 1690
url: /el/aspose.slides.charts/iaxis/
---
## IAxis διεπαφή

Encapsulates the object that represents a chart's axis.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα της κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Καθορίζει την πραγματική κλίμακα της δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IFormattedTextContainer. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Αντιπροσωπεύει αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν ισχύει για 3-Δ γραφήματα. Ανάγνωση/εγγραφή Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Καθορίζει τη μικρότερη μονάδα χρόνου που αντιπροσωπεύεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Καθορίζει το πλάτος του κάδου όταν η τιμή της ιδιότητας AggregationType είναι AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Αντιπροσωπεύει το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας τον διασχίζει. Ανάγνωση/εγγραφή [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Αντιπροσωπεύει τη μορφή του άξονα. Μόνο για ανάγνωση [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Καθορίζει αν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Δείχνει αν η κύρια μονάδα του άξονα έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Δείχνει αν η μέγιστη τιμή έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Δείχνει αν η δευτερεύουσα μονάδα του άξονα έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Δείχνει αν η ελάχιστη τιμή έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή του overflow bin. Αν ψευδές: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης ετικετών κεντήματος. Αν ψευδές: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Καθορίζει την αυτόματη τιμή απόστασης σημείων κεντήματος. Αν ψευδές: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Καθορίζει την αυτόματη τιμή του underflow bin. Αν ψευδές: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Αντιπροσωπεύει αν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Δείχνει αν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. Ανάγνωση/εγγραφή Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Καθορίζει αν εφαρμόστηκε overflow bin. Χρησιμοποιήστε τις IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bin. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Αντιπροσωπεύει αν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Καθορίζει αν εφαρμόστηκε underflow bin. Χρησιμοποιήστε τις IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bin. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Αντιπροσωπεύει αν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Αντιπροσωπεύει τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο του κύριου δεικτικού σήματος για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Αντιπροσωπεύει τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Αντιπροσωπεύει τον τύπο του δευτερεύοντος δεικτικού σήματος για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες άξονα. Ανάγνωση/εγγραφή String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType είναι AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι ψευδής και η ιδιότητα IsOverflowBin είναι αληθής. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Αντιπροσωπεύει τη θέση του άξονα. Ανάγνωση/εγγραφή [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Αντιπροσωπεύει αν εμφανίζονται οι κύριες γραμμές πλέγματος. Μόνο για ανάγνωση Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Αντιπροσωπεύει αν εμφανίζονται οι δευτερεύουσες γραμμές πλέγματος. Μόνο για ανάγνωση Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Αντιπροσωπεύει τη θέση των ετικετών των σημείων κεντήματος στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών κεντήματος. Ανάγνωση/εγγραφή Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Καθορίζει πόσες ετικέτες κεντήματος θα παραληφθούν μεταξύ των ετικετών που σχεδιάζονται. Ανάγνωση/εγγραφή UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Καθορίζει πόσα σημεία κεντήματος θα παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Αποκτά τον τίτλο του άξονα. Μόνο για ανάγνωση [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι ψευδής και η ιδιότητα IsUnderflowBin είναι αληθής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Ορίζει την ιδιότητα IAxis.CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |

### Δείτε επίσης

* διεπαφή [IFormattedTextContainer](../iformattedtextcontainer)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->