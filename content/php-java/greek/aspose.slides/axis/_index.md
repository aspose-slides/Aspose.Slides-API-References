---
title: Axis
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/axis/
---
## Axis κλάση

 Κατοχυρώνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
 
### getActualMajorUnit {#getActualMajorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualMajorUnit () | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |

 **Επιστρέφει:**
double


---


### getActualMajorUnitScale {#getActualMajorUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualMajorUnitScale () | Καθορίζει την πραγματική κλίμακα της κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |

 **Επιστρέφει:**
int


---


### getActualMaxValue {#getActualMaxValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualMaxValue () | Καθορίζει τη πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |

 **Επιστρέφει:**
double


---


### getActualMinValue {#getActualMinValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualMinValue () | Καθορίζει τη πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |

 **Επιστρέφει:**
double


---


### getActualMinorUnit {#getActualMinorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualMinorUnit () | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |

 **Επιστρέφει:**
double


---


### getActualMinorUnitScale {#getActualMinorUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualMinorUnitScale () | Καθορίζει την πραγματική κλίμακα της δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |

 **Επιστρέφει:**
int


---


### getAggregationType {#getAggregationType}

| Όνομα | Περιγραφή |
| --- | --- |
| getAggregationType () | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |

 **Επιστρέφει:**
int


---


### getAxisBetweenCategories {#getAxisBetweenCategories}

| Όνομα | Περιγραφή |
| --- | --- |
| getAxisBetweenCategories () | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο στους άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getBaseUnitScale {#getBaseUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getBaseUnitScale () | Καθορίζει τη μικρότερη χρονική μονάδα που αντιπροσωπεύεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή TimeUnitType. |

 **Επιστρέφει:**
int


---


### getBinWidth {#getBinWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getBinWidth () | Καθορίζει το πλάτος bin όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |

 **Επιστρέφει:**
double


---


### getCategoryAxisType {#getCategoryAxisType}

| Όνομα | Περιγραφή |
| --- | --- |
| getCategoryAxisType () | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή CategoryAxisType. |

 **Επιστρέφει:**
int


---


### getChart {#getChart}

| Όνομα | Περιγραφή |
| --- | --- |
| getChart () | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση IChart. |

 **Επιστρέφει:**
[Chart](../chart)


---


### getCrossAt {#getCrossAt}

| Όνομα | Περιγραφή |
| --- | --- |
| getCrossAt () | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float. |

 **Επιστρέφει:**
float


---


### getCrossType {#getCrossType}

| Όνομα | Περιγραφή |
| --- | --- |
| getCrossType () | Αντιπροσωπεύει το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. Ανάγνωση/εγγραφή CrossesType. |

 **Επιστρέφει:**
int


---


### getDisplayUnit {#getDisplayUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisplayUnit () | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή DisplayUnitType. |

 **Επιστρέφει:**
int


---


### getFormat {#getFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormat () | Αντιπροσωπεύει τη μορφή του άξονα. Μόνο για ανάγνωση IAxisFormat. |

 **Επιστρέφει:**
[AxisFormat](../axisformat)


---


### getLabelOffset {#getLabelOffset}

| Όνομα | Περιγραφή |
| --- | --- |
| getLabelOffset () | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int. |

 **Επιστρέφει:**
int


---


### getLogBase {#getLogBase}

| Όνομα | Περιγραφή |
| --- | --- |
| getLogBase () | Αντιπροσωπεύει τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMajorGridLinesFormat {#getMajorGridLinesFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getMajorGridLinesFormat () | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση IChartLinesFormat. |

 **Επιστρέφει:**
[ChartLinesFormat](../chartlinesformat)


---


### getMajorTickMark {#getMajorTickMark}

| Όνομα | Περιγραφή |
| --- | --- |
| getMajorTickMark () | Αντιπροσωπεύει τον τύπο του κύριου σημείου στίγματος για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή TickMarkType. |

 **Επιστρέφει:**
int


---


### getMajorUnit {#getMajorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| getMajorUnit () | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMajorUnitScale {#getMajorUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getMajorUnitScale () | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή TimeUnitType. |

 **Επιστρέφει:**
int


---


### getMaxValue {#getMaxValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getMaxValue () | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMinValue {#getMinValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinValue () | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMinorGridLinesFormat {#getMinorGridLinesFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinorGridLinesFormat () | Αντιπροσωπεύει τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση IChartLinesFormat. |

 **Επιστρέφει:**
[ChartLinesFormat](../chartlinesformat)


---


### getMinorTickMark {#getMinorTickMark}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinorTickMark () | Αντιπροσωπεύει τον τύπο του δευτερεύοντος σημείου στίγματος για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή TickMarkType. |

 **Επιστρέφει:**
int


---


### getMinorUnit {#getMinorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinorUnit () | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMinorUnitScale {#getMinorUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinorUnitScale () | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή TimeUnitType. |

 **Επιστρέφει:**
int


---


### getNumberFormat {#getNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberFormat () | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες άξονα. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
String


---


### getNumberOfBins {#getNumberOfBins}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberOfBins () | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |

 **Επιστρέφει:**
long


---


### getOverflowBin {#getOverflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| getOverflowBin () | Καθορίζει την προσαρμοσμένη τιμή του overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin είναι true. |

 **Επιστρέφει:**
double


---


### getPosition {#getPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| getPosition () | Αντιπροσωπεύει τη θέση του άξονα. Ανάγνωση/εγγραφή AxisPositionType. |

 **Επιστρέφει:**
int


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την κύρια παρουσίαση ενός FillFormat. Μόνο για ανάγνωση IPresentation. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getShowMajorGridLines {#getShowMajorGridLines}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMajorGridLines () | Για την απόκρυψη της κύριας γραμμής πλέγματος ορίστε το MajorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο για ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### getShowMinorGridLines {#getShowMinorGridLines}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMinorGridLines () | Για την απόκρυψη της δευτερεύουσας γραμμής πλέγματος ορίστε το MinorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο για ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση BaseSlide. |

 **Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTextFormat {#getTextFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getTextFormat () | Αντιπροσωπεύει τη μορφή του κειμένου. Μόνο για ανάγνωση IChartTextFormat. |

 **Επιστρέφει:**
[ChartTextFormat](../charttextformat)


---


### getTickLabelPosition {#getTickLabelPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| getTickLabelPosition () | Αντιπροσωπεύει τη θέση των ετικετών των σημείων στίγματος στον καθορισμένο άξονα. Ανάγνωση/εγγραφή TickLabelPositionType. |

 **Επιστρέφει:**
int


---


### getTickLabelRotationAngle {#getTickLabelRotationAngle}

| Όνομα | Περιγραφή |
| --- | --- |
| getTickLabelRotationAngle () | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σημείων στίγματος. Ανάγνωση/εγγραφή float. |

 **Επιστρέφει:**
float


---


### getTickLabelSpacing {#getTickLabelSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| getTickLabelSpacing () | Καθορίζει πόσες ετικέτες σημείων στίγματος θα παραλειφθούν μεταξύ των ετικετών που σχεδιάζονται. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή long. |

 **Επιστρέφει:**
long


---


### getTickMarksSpacing {#getTickMarksSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| getTickMarksSpacing () | Καθορίζει πόσα σημεία στίγματος θα παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int. |

 **Επιστρέφει:**
long


---


### getTitle {#getTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| getTitle () | Αποκτά τον τίτλο του άξονα. Μόνο για ανάγνωση IChartTitle. |

 **Επιστρέφει:**
[ChartTitle](../charttitle)


---


### getUnderflowBin {#getUnderflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| getUnderflowBin () | Καθορίζει την προσαρμοσμένη τιμή του underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin είναι true. |

 **Επιστρέφει:**
double


---


### hasTitle {#hasTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| hasTitle () | Καθορίζει αν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isAutomaticMajorUnit {#isAutomaticMajorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticMajorUnit () | Δείχνει αν η κύρια μονάδα του άξονα έχει ανατεθεί αυτόματα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isAutomaticMaxValue {#isAutomaticMaxValue}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticMaxValue () | Δείχνει αν η μέγιστη τιμή έχει ανατεθεί αυτόματα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isAutomaticMinValue {#isAutomaticMinValue}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticMinValue () | Δείχνει αν η ελάχιστη τιμή έχει ανατεθεί αυτόματα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isAutomaticMinorUnit {#isAutomaticMinorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticMinorUnit () | Δείχνει αν η δευτερεύουσα μονάδα του άξονα έχει ανατεθεί αυτόματα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isAutomaticOverflowBin {#isAutomaticOverflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticOverflowBin () | Καθορίζει την αυτόματη τιμή του overflow bin. Εάν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin. |

 **Επιστρέφει:**
boolean


---


### isAutomaticTickLabelSpacing {#isAutomaticTickLabelSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticTickLabelSpacing () | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημείων στίγματος. Εάν είναι false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isAutomaticTickMarksSpacing {#isAutomaticTickMarksSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticTickMarksSpacing () | Καθορίζει την αυτόματη τιμή απόστασης σημείων στίγματος. Εάν είναι false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---
### isAutomaticUnderflowBin {#isAutomaticUnderflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| isAutomaticUnderflowBin () | Καθορίζει την αυτόματη τιμή του bin υπογλώσσης. Αν ψευδές: χρησιμοποιήστε την ιδιότητα UnderflowBin. |

**Επιστρέφει:**  
boolean


---


### isLogarithmic {#isLogarithmic}

| Όνομα | Περιγραφή |
| --- | --- |
| isLogarithmic () | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
boolean


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Όνομα | Περιγραφή |
| --- | --- |
| isNumberFormatLinkedToSource () | Δείχνει αν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
boolean


---


### isOverflowBin {#isOverflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| isOverflowBin () | Καθορίζει εάν εφαρμόζεται bin υπερχείλισης. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bin. |

**Επιστρέφει:**  
boolean


---


### isPlotOrderReversed {#isPlotOrderReversed}

| Όνομα | Περιγραφή |
| --- | --- |
| isPlotOrderReversed () | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
boolean


---


### isUnderflowBin {#isUnderflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| isUnderflowBin () | Καθορίζει εάν εφαρμόζεται bin υπογλώσσης. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bin. |

**Επιστρέφει:**  
boolean


---


### isVisible {#isVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| isVisible () | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
boolean


---


### setAggregationType {#setAggregationType}

| Όνομα | Περιγραφή |
| --- | --- |
| setAggregationType (int) | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (binning). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |

**Επιστρέφει:**  
void


---


### setAutomaticMajorUnit {#setAutomaticMajorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticMajorUnit (boolean) | Δείχνει εάν η κύρια μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setAutomaticMaxValue {#setAutomaticMaxValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticMaxValue (boolean) | Δείχνει εάν η μέγιστη τιμή εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setAutomaticMinValue {#setAutomaticMinValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticMinValue (boolean) | Δείχνει εάν η ελάχιστη τιμή εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setAutomaticMinorUnit {#setAutomaticMinorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticMinorUnit (boolean) | Δείχνει εάν η δευτερεύουσα μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setAutomaticOverflowBin {#setAutomaticOverflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticOverflowBin (boolean) | Καθορίζει την αυτόματη τιμή του overflow bin. Αν ψευδές: χρησιμοποιήστε την ιδιότητα OverflowBin. |

**Επιστρέφει:**  
void


---


### setAutomaticTickLabelSpacing {#setAutomaticTickLabelSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticTickLabelSpacing (boolean) | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημείων. Αν ψευδές: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setAutomaticTickMarksSpacing {#setAutomaticTickMarksSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticTickMarksSpacing (boolean) | Καθορίζει την αυτόματη τιμή απόστασης σημείων σημάνσεων. Αν ψευδές: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setAutomaticUnderflowBin {#setAutomaticUnderflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| setAutomaticUnderflowBin (boolean) | Καθορίζει την αυτόματη τιμή του underflow bin. Αν ψευδές: χρησιμοποιήστε την ιδιότητα UnderflowBin. |

**Επιστρέφει:**  
void


---


### setAxisBetweenCategories {#setAxisBetweenCategories}

| Όνομα | Περιγραφή |
| --- | --- |
| setAxisBetweenCategories (boolean) | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setBaseUnitScale {#setBaseUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| setBaseUnitScale (int) | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή TimeUnitType. |

**Επιστρέφει:**  
void


---


### setBinWidth {#setBinWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| setBinWidth (double) | Καθορίζει το πλάτος του bin όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |

**Επιστρέφει:**  
void


---


### setCategoryAxisType {#setCategoryAxisType}

| Όνομα | Περιγραφή |
| --- | --- |
| setCategoryAxisType (int) | Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή CategoryAxisType. |

**Επιστρέφει:**  
void


---


### setCategoryAxisTypeAutomatically {#setCategoryAxisTypeAutomatically}

| Όνομα | Περιγραφή |
| --- | --- |
| setCategoryAxisTypeAutomatically () | Ορίζει την ιδιότητα IAxis.CategoryAxisType με τιμή που προσδιορίζεται αυτόματα βάσει των δεδομένων του άξονα. |

**Επιστρέφει:**  
void


---


### setCrossAt {#setCrossAt}

| Όνομα | Περιγραφή |
| --- | --- |
| setCrossAt (float) | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**  
void


---


### setCrossType {#setCrossType}

| Όνομα | Περιγραφή |
| --- | --- |
| setCrossType (int) | Αντιπροσωπεύει το CrossType στον καθορισμένο άξονα όπου διασχίζεται από τον άλλο άξονα. Ανάγνωση/εγγραφή CrossesType. |

**Επιστρέφει:**  
void


---


### setDisplayUnit {#setDisplayUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisplayUnit (int) | Καθορίζει την τιμή κλιμάκωσης των μονάδων προβολής για τον άξονα τιμών. Ανάγνωση/εγγραφή DisplayUnitType. |

**Επιστρέφει:**  
void


---


### setLabelOffset {#setLabelOffset}

| Όνομα | Περιγραφή |
| --- | --- |
| setLabelOffset (int) | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int. |

**Επιστρέφει:**  
void


---


### setLogBase {#setLogBase}

| Όνομα | Περιγραφή |
| --- | --- |
| setLogBase (double) | Αντιπροσωπεύει τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double. |

**Επιστρέφει:**  
void


---


### setLogarithmic {#setLogarithmic}

| Όνομα | Περιγραφή |
| --- | --- |
| setLogarithmic (boolean) | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setMajorTickMark {#setMajorTickMark}

| Όνομα | Περιγραφή |
| --- | --- |
| setMajorTickMark (int) | Αντιπροσωπεύει τον τύπο του κύριου σημείου σήμανσης για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή TickMarkType. |

**Επιστρέφει:**  
void


---


### setMajorUnit {#setMajorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| setMajorUnit (double) | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή double. |

**Επιστρέφει:**  
void


---


### setMajorUnitScale {#setMajorUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| setMajorUnitScale (int) | Αντιπροσωπεύει την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή TimeUnitType. |

**Επιστρέφει:**  
void


---


### setMaxValue {#setMaxValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setMaxValue (double) | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double. |

**Επιστρέφει:**  
void


---


### setMinValue {#setMinValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setMinValue (double) | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double. |

**Επιστρέφει:**  
void


---


### setMinorTickMark {#setMinorTickMark}

| Όνομα | Περιγραφή |
| --- | --- |
| setMinorTickMark (int) | Αντιπροσωπεύει τον τύπο του δευτερεύοντος σημείου σήμανσης για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή TickMarkType. |

**Επιστρέφει:**  
void


---


### setMinorUnit {#setMinorUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| setMinorUnit (double) | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμών. Ανάγνωση/εγγραφή double. |

**Επιστρέφει:**  
void


---


### setMinorUnitScale {#setMinorUnitScale}

| Όνομα | Περιγραφή |
| --- | --- |
| setMinorUnitScale (int) | Αντιπροσωπεύει την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή TimeUnitType. |

**Επιστρέφει:**  
void


---


### setNumberFormat {#setNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormat (String) | Αντιπροσωπεύει τη συμβολοσειρά μορφοποίησης για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**  
void


---


### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Δείχνει εάν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setNumberOfBins {#setNumberOfBins}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberOfBins (long) | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |

**Επιστρέφει:**  
void


---


### setOverflowBin {#setOverflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| setOverflowBin (boolean) | Καθορίζει εάν εφαρμόζεται bin υπερχείλισης. Χρησιμοποιήστε IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bin. |

**Επιστρέφει:**  
void


---


### setOverflowBin {#setOverflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| setOverflowBin (double) | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε ψευδές και η ιδιότητα IsOverflowBin είναι true. |

**Επιστρέφει:**  
void


---


### setPlotOrderReversed {#setPlotOrderReversed}

| Όνομα | Περιγραφή |
| --- | --- |
| setPlotOrderReversed (boolean) | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setPosition {#setPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| setPosition (int) | Αντιπροσωπεύει τη θέση του άξονα. Ανάγνωση/εγγραφή AxisPositionType. |

**Επιστρέφει:**  
void


---


### setTickLabelPosition {#setTickLabelPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| setTickLabelPosition (int) | Αντιπροσωπεύει τη θέση των ετικετών σημείασσημασμάτων στον καθορισμένο άξονα. Ανάγνωση/εγγραφή TickLabelPositionType. |

**Επιστρέφει:**  
void


---


### setTickLabelRotationAngle {#setTickLabelRotationAngle}

| Όνομα | Περιγραφή |
| --- | --- |
| setTickLabelRotationAngle (float) | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών των σημείασσημασμάτων. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**  
void


---


### setTickLabelSpacing {#setTickLabelSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| setTickLabelSpacing (long) | Καθορίζει πόσες ετικέτες σημείασσημασμάτων θα παραλειφθούν μεταξύ των σχεδιασμένων. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή long. |

**Επιστρέφει:**  
void


---


### setTickMarksSpacing {#setTickMarksSpacing}

| Όνομα | Περιγραφή |
| --- | --- |
| setTickMarksSpacing (long) | Καθορίζει πόσα σημείασσημαστικά σημεία θα παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int. |

**Επιστρέφει:**  
void


---


### setTitle {#setTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| setTitle (boolean) | Καθορίζει εάν ένας άξονας διαθέτει ορατό τίτλο. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---


### setUnderflowBin {#setUnderflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| setUnderflowBin (boolean) | Καθορίζει εάν εφαρμόζεται bin υπογλώσσης. Χρησιμοποιήστε IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bin. |

**Επιστρέφει:**  
void


---


### setUnderflowBin {#setUnderflowBin}

| Όνομα | Περιγραφή |
| --- | --- |
| setUnderflowBin (double) | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε ψευδές και η ιδιότητα IsUnderflowBin είναι true. |

**Επιστρέφει:**  
void


---


### setVisible {#setVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| setVisible (boolean) | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
void


---