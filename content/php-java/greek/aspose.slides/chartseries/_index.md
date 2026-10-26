---
title: ChartSeries
second_title: Αναφορά API Aspose.Sildes για PHP μέσω Java
description: 
type: docs

url: /el/aspose.slides/chartseries/
---
## ChartSeries κλάση

Αντιπροσωπεύει μια σειρά διαγράμματος.

### getAutomaticSeriesColor {#getAutomaticSeriesColor}

| Όνομα | Περιγραφή |
| --- | --- |
| getAutomaticSeriesColor () | Επιστρέφει ένα αυτόματο χρώμα της σειράς βάσει του δείκτη της σειράς και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType ισούται με NotDefined. |

**Επιστρέφει:**  
Color


---


### getBar3DShape {#getBar3DShape}

| Όνομα | Περιγραφή |
| --- | --- |
| getBar3DShape () | Καθορίζει το σχήμα μιας σειράς ενός 3-Δ ραβδικού διαγράμματος. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του τύπου της σειράς. Ανάγνωση/εγγραφή ChartShapeType. |

**Επιστρέφει:**  
int


---


### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getBubbleSizeRepresentation () | Καθορίζει πώς οι τιμές μεγέθους των φυσαλίδων εμφανίζονται στο διάγραμμα φυσαλίδων. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeRepresentation ανάγνωση/εγγραφή για αλλαγή τιμής. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeRepresentation. |

**Επιστρέφει:**  
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| Όνομα | Περιγραφή |
| --- | --- |
| getBubbleSizeScale () | Καθορίζει το συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προκαθορισμένου μεγέθους). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeScale ανάγνωση/εγγραφή για αλλαγή τιμής. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.BubbleSizeScale. |

**Επιστρέφει:**  
int


---


### getChart {#getChart}

| Όνομα | Περιγραφή |
| --- | --- |
| getChart () | Επιστρέφει το γονικό διάγραμμα. Μόνο ανάγνωση IChart. |

**Επιστρέφει:**  
[Chart](../chart)


---


### getDataPoints {#getDataPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getDataPoints () | Επιστρέφει τη συλλογή σημείων δεδομένων αυτής της σειράς. Μόνο ανάγνωση IChartDataPointCollection. |

**Επιστρέφει:**  
[ChartDataPointCollection](../chartdatapointcollection)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getDoughnutHoleSize () | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.DoughnutHoleSize ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο ανάγνωση byte. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.DoughnutHoleSize. |

**Επιστρέφει:**  
byte


---


### getErrorBarsXFormat {#getErrorBarsXFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getErrorBarsXFormat () | Αντιπροσωπεύει τα ErrorBars της σειράς με κατεύθυνση X. Μόνο ανάγνωση IErrorBarsFormat. Τα ErrorBars με κατεύθυνση X είναι διαθέσιμα για σειρές τύπου area, bar, scatter και bubble. Για οποιοδήποτε άλλο τύπο διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να ορίσετε την τιμή (με την ιδιότητα ( IChartDataPoint#getErrorBarsCustomValues)). |

**Επιστρέφει:**  
[ErrorBarsFormat](../errorbarsformat)


---


### getErrorBarsYFormat {#getErrorBarsYFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getErrorBarsYFormat () | Αντιπροσωπεύει τα ErrorBars της σειράς με κατεύθυνση Y. Μόνο ανάγνωση IErrorBarsFormat. Τα ErrorBars με κατεύθυνση Y είναι διαθέσιμα για σειρές τύπου area, bar, line, scatter και bubble. Για οποιοδήποτε άλλο τύπο διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να ορίσετε την τιμή (με την ιδιότητα ( IChartDataPoint#getErrorBarsCustomValues)). |

**Επιστρέφει:**  
[ErrorBarsFormat](../errorbarsformat)


---


### getExplosion {#getExplosion}

| Όνομα | Περιγραφή |
| --- | --- |
| getExplosion () | Η απόσταση ενός ανοιχτού τμήματος πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Ανάγνωση/εγγραφή int. |

**Επιστρέφει:**  
int


---


### getFirstSliceAngle {#getFirstSliceAngle}

| Όνομα | Περιγραφή |
| --- | --- |
| getFirstSliceAngle () | Καθορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από το πάνω, από 0 έως 360 μοίρες). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.FirstSliceAngle ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο ανάγνωση int. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.FirstSliceAngle. |

**Επιστρέφει:**  
int


---


### getFormat {#getFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormat () | Επιστρέφει τη μορφή μιας σειράς. Μόνο ανάγνωση IFormat. |

**Επιστρέφει:**  
[Format](../format)


---


### getGapDepth {#getGapDepth}

| Όνομα | Περιγραφή |
| --- | --- |
| getGapDepth () | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3D διάγραμμα. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapDepth ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο ανάγνωση int. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.GapDepth. |

**Επιστρέφει:**  
int


---


### getGapWidth {#getGapWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getGapWidth () | Καθορίζει το χώρο μεταξύ ομάδων ραβδών ή στηλών, ως ποσοστό του πλάτους της ράβδου ή στήλης. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapWidth ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο ανάγνωση int. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.GapWidth. |

**Επιστρέφει:**  
int


---


### getInvertIfNegative {#getInvertIfNegative}

| Όνομα | Περιγραφή |
| --- | --- |
| getInvertIfNegative () | Καθορίζει εάν η σειρά ραβδών, στηλών ή φυσαλίδων θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
boolean


---


### getInvertedSolidFillColor {#getInvertedSolidFillColor}

| Όνομα | Περιγραφή |
| --- | --- |
| getInvertedSolidFillColor () | Καθορίζει το αντιστροφό solid χρώμα για τη σειρά. Για να εφαρμοστεί η ρύθμιση χρώματος, ορίστε το FillType της μορφής σειράς στο FillType.Solid. Ανάγνωση/εγγραφή ColorFormat. |

**Επιστρέφει:**  
[ColorFormat](../colorformat)


---


### getLabels {#getLabels}

| Όνομα | Περιγραφή |
| --- | --- |
| getLabels () | Επιστρέφει τις Ετικέτες μιας σειράς. Μόνο ανάγνωση IDataLabelCollection. |

**Επιστρέφει:**  
[DataLabelCollection](../datalabelcollection)


---


### getMarker {#getMarker}

| Όνομα | Περιγραφή |
| --- | --- |
| getMarker () | Δείκτης. Μόνο ανάγνωση IMarker. |

**Επιστρέφει:**  
[Marker](../marker)


---


### getName {#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName () | Επιστρέφει το όνομα της σειράς. Μόνο ανάγνωση IStringChartValue. |

**Επιστρέφει:**  
[StringChartValue](../stringchartvalue)


---


### getNumberFormatOfBubbleSizes {#getNumberFormatOfBubbleSizes}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberFormatOfBubbleSizes () | NumberFormatOfBubbleSizes. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**  
String


---


### getNumberFormatOfValues {#getNumberFormatOfValues}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberFormatOfValues () | NumberFormatOfValues. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**  
String


---


### getNumberFormatOfXValues {#getNumberFormatOfXValues}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberFormatOfXValues () | NumberFormatOfXValues. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**  
String


---


### getNumberFormatOfYValues {#getNumberFormatOfYValues}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberFormatOfYValues () | NumberFormatOfYValues. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**  
String


---


### getOrder {#getOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| getOrder () | Επιστρέφει τη σειρά μιας σειράς. Ανάγνωση/εγγραφή int. |

**Επιστρέφει:**  
int


---


### getOverlap {#getOverlap}

| Όνομα | Περιγραφή |
| --- | --- |
| getOverlap () | Καθορίζει το πόσο οι ράβδοι και στήλες επικαλύπτονται σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών. Είναι προβολή της αντίστοιχης ιδιότητας στην γονική ομάδα σειρών, και συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Για αλλαγή της τιμής, χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.Overlap ανάγνωση/εγγραφή. Μόνο ανάγνωση byte. Η Overlap καθορίζει το βαθμό επικάλυψης ή διαχωρισμού μεταξύ ράβδων και στηλών ως ποσοστό του πλάτους τους: -100%: Μέγιστος διαχωρισμός (οι ράβδοι είναι εντελώς χωρισμένοι). 0%: Οι ράβδοι τοποθετούνται δίπλα-δίπλα χωρίς επικάλυψη ή διαχωρισμό. 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.Overlap. |

**Επιστρέφει:**  
byte


---


### getParentLabelLayout {#getParentLabelLayout}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentLabelLayout () | Αντιπροσωπεύει τη διάταξη των ετικετών γονικής κατηγορίας. Ισχύει μόνο για διαγράμματα Treemap. |

**Επιστρέφει:**  
int


---


### getParentSeriesGroup {#getParentSeriesGroup}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentSeriesGroup () | ParentSeriesGroup. Μόνο ανάγνωση IChartSeriesGroup. |

**Επιστρέφει:**  
[ChartSeriesGroup](../chartseriesgroup)


---


### getPieSplitBy {#getPieSplitBy}

| Όνομα | Περιγραφή |
| --- | --- |
| getPieSplitBy () | Καθορίζει πώς θα προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα pie-of-pie ή bar-of-pie. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitBy ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο ανάγνωση PieSplitType. 1) Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.PieSplitBy. 2) Εάν η τιμή της ιδιότητας είναι PieSplitType.Custom, μπορείτε να ορίσετε προσαρμοσμένες πληροφορίες διαίρεσης με την ιδιότητα ParentSeriesGroup.PieSplitCustomPoints. |

**Επιστρέφει:**  
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getPieSplitCustomPoints () | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα pie-of-pie ή bar-of-pie με προσαρμοσμένη διαίρεση. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Μόνο ανάγνωση PieSplitCustomPointCollection. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.PieSplitCustomPoints. |

**Επιστρέφει:**  
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| getPieSplitPosition () | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – αποτελεί προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitPosition ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο ανάγνωση double. Πρόκειται για την προβολή της ιδιότητας ParentSeriesGroup.PieSplitPosition. |

**Επιστρέφει:**  
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| Όνομα | Περιγραφή |
| --- | --- |
| getPlotOnSecondAxis () | Δείχνει εάν αυτή η σειρά σχεδιάζεται σε δευτερεύοντα άξονα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**  
boolean


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () |  |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση IPresentation. |

**Επιστρέφει:**
[Presentation](../presentation)

---

### getQuartileMethod {#getQuartileMethod}

| Όνομα | Περιγραφή |
| --- | --- |
| getQuartileMethod () | Αντιπροσωπεύει τη μέθοδο τεταρτημόριου. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. |

**Επιστρέφει:**
int

---

### getRelatedLegendEntry {#getRelatedLegendEntry}

| Όνομα | Περιγραφή |
| --- | --- |
| getRelatedLegendEntry () | Αντιπροσωπεύει την καταχώριση υπομνήματος σχετική με αυτή τη σειρά. Μόνο για ανάγνωση ILegendEntryProperties. |

**Επιστρέφει:**
[LegendEntryProperties](../legendentryproperties)

---

### getSecondPieSize {#getSecondPieSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getSecondPieSize () | Καθορίζει το μέγεθος του δεύτερου πίτας ή ράβδου ενός διαγράμματος πίτας-με-πίτα ή ράβδου-με-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SecondPieSize ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση int. Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.SecondPieSize. |

**Επιστρέφει:**
int

---

### getShowConnectorLines {#getShowConnectorLines}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowConnectorLines () | Αντιπροσωπεύει τις γραμμές σύνδεσης. Εφαρμόζεται μόνο σε διαγράμματα Waterfall. |

**Επιστρέφει:**
boolean

---

### getShowInnerPoints {#getShowInnerPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowInnerPoints () | Αντιπροσωπεύει τα εσωτερικά σημεία. Αληθές αν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getShowMeanLine {#getShowMeanLine}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMeanLine () | Αντιπροσωπεύει τη μέση γραμμή. Αληθές αν η μέση γραμμή εμφανίζεται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getShowMeanMarkers {#getShowMeanMarkers}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMeanMarkers () | Αντιπροσωπεύει τα δείκτες μέσης τιμής. Αληθές αν οι δείκτες μέσης τιμής εμφανίζονται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getShowOutlierPoints {#getShowOutlierPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowOutlierPoints () | Αντιπροσωπεύει τα σημεία εκτός ορίων. Αληθές αν τα σημεία εκτός ορίων εμφανίζονται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

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

### getSmooth {#getSmooth}

| Όνομα | Περιγραφή |
| --- | --- |
| getSmooth () | Αντιπροσωπεύει την εξομάλυνση καμπύλης. Αληθές αν η εξομάλυνση καμπύλης ενεργοποιείται για το διάγραμμα γραμμής ή το διάγραμμα scatter. Εφαρμόζεται μόνο σε διαγράμματα γραμμής και scatter που συνδέονται με γραμμές. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getTrendLines {#getTrendLines}

| Όνομα | Περιγραφή |
| --- | --- |
| getTrendLines () | Συλλογή γραμμών τάσης σειράς. Μόνο για ανάγνωση ITrendlineCollection. Οι TrendLines είναι διαθέσιμες (μη μηδενικές) για σειρές δεδομένων σε διαγράμματα 2Δ μη στοίβαξης περιοχής, ράβδου, στήλης, γραμμής, μετοχών, xy (scatter) και φυσαλίδων. Η γραμμή τάσης δεν είναι διαθέσιμη για σειρές δεδομένων σε οποιοδήποτε τύπο διαγράμματος που είναι στοίβαξη ή 3Δ. Οι Trendlines δεν είναι επίσης διαθέσιμες για διαγράμματα radar, πίτας, επιφάνειας ή δακτυλίου. |

**Επιστρέφει:**
[TrendlineCollection](../trendlinecollection)

---

### getType {#getType}

| Όνομα | Περιγραφή |
| --- | --- |
| getType () | Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/Εγγραφή ChartType. |

**Επιστρέφει:**
int

---

### hasSeriesLines {#hasSeriesLines}

| Όνομα | Περιγραφή |
| --- | --- |
| hasSeriesLines () | Καθορίζει εάν υπάρχουν γραμμές σειράς για αυτή τη σειρά και συγγενείς σειρές. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.HasSeriesLines ανάγνωση/εγγραφή για αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SeriesLinesFormat για μορφοποίηση γραμμών σειράς. Μόνο για ανάγνωση boolean. Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.HasSeriesLines. |

**Επιστρέφει:**
boolean

---

### hasUpDownBars {#hasUpDownBars}

| Όνομα | Περιγραφή |
| --- | --- |
| hasUpDownBars () | Καθορίζει εάν το διάγραμμα Line ή Stock έχει ράβδους ανοδική/καθοδική. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars.HasUpDownBars ανάγνωση/εγγραφή για αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars για μορφοποίηση ραβδών ανοδική/καθοδική. Μόνο για ανάγνωση boolean. Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.UpDownBars.HasUpDownBars. |

**Επιστρέφει:**
boolean

---

### isColorVaried {#isColorVaried}

| Όνομα | Περιγραφή |
| --- | --- |
| isColorVaried () | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – είναι προβολή της αντίστοιχης ιδιότητας ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.IsColorVaried ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση boolean. Αυτή είναι η προβολή της ιδιότητας ParentSeriesGroup.IsColorVaried. |

**Επιστρέφει:**
boolean

---

### setBar3DShape {#setBar3DShape}

| Όνομα | Περιγραφή |
| --- | --- |
| setBar3DShape (int) | Καθορίζει το σχήμα μιας σειράς σε διάγραμμα 3Δ ράβδου. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του Type της σειράς. Ανάγνωση/Εγγραφή ChartShapeType. |

**Επιστρέφει:**
void

---

### setExplosion {#setExplosion}

| Όνομα | Περιγραφή |
| --- | --- |
| setExplosion (int) | Η απόσταση ενός ανοικτού κομματιού πίτας από το κέντρο του διαγράμματος πίτας εκφράζεται ως ποσοστό της διαμέτρου της πίτας. Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void

---

### setInvertIfNegative {#setInvertIfNegative}

| Όνομα | Περιγραφή |
| --- | --- |
| setInvertIfNegative (boolean) | Καθορίζει ότι η σειρά ράβδου, στήλης ή φυσαλίδας θα αντιστρέψει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setNumberFormatOfBubbleSizes {#setNumberFormatOfBubbleSizes}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormatOfBubbleSizes (String) | NumberFormatOfBubbleSizes. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
void

---

### setNumberFormatOfValues {#setNumberFormatOfValues}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormatOfValues (String) | NumberFormatOfValues. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
void

---

### setNumberFormatOfXValues {#setNumberFormatOfXValues}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormatOfXValues (String) | NumberFormatOfXValues. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
void

---

### setNumberFormatOfYValues {#setNumberFormatOfYValues}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormatOfYValues (String) | NumberFormatOfYValues. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
void

---

### setOrder {#setOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| setOrder (int) | Επιστρέφει τη σειρά μιας σειράς. Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void

---

### setParentLabelLayout {#setParentLabelLayout}

| Όνομα | Περιγραφή |
| --- | --- |
| setParentLabelLayout (int) | Αντιπροσωπεύει τη διάταξη των ετικετών γονικής κατηγορίας. Εφαρμόζεται μόνο σε διαγράμματα Treemap. |

**Επιστρέφει:**
void

---

### setPlotOnSecondAxis {#setPlotOnSecondAxis}

| Όνομα | Περιγραφή |
| --- | --- |
| setPlotOnSecondAxis (boolean) | Υποδεικνύει εάν αυτή η σειρά απεικονίζεται στον δευτερεύον άξονα. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setQuartileMethod {#setQuartileMethod}

| Όνομα | Περιγραφή |
| --- | --- |
| setQuartileMethod (int) | Αντιπροσωπεύει τη μέθοδο τεταρτημόριου. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. |

**Επιστρέφει:**
void

---

### setShowConnectorLines {#setShowConnectorLines}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowConnectorLines (boolean) | Αντιπροσωπεύει τις γραμμές σύνδεσης. Εφαρμόζεται μόνο σε διαγράμματα Waterfall. |

**Επιστρέφει:**
void

---

### setShowInnerPoints {#setShowInnerPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowInnerPoints (boolean) | Αντιπροσωπεύει τα εσωτερικά σημεία. Αληθές αν τα εσωτερικά σημεία εμφανίζονται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setShowMeanLine {#setShowMeanLine}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowMeanLine (boolean) | Αντιπροσωπεύει τη μέση γραμμή. Αληθές αν η μέση γραμμή εμφανίζεται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setShowMeanMarkers {#setShowMeanMarkers}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowMeanMarkers (boolean) | Αντιπροσωπεύει τους δείκτες μέσης τιμής. Αληθές αν οι δείκτες μέσης τιμής εμφανίζονται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setShowOutlierPoints {#setShowOutlierPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowOutlierPoints (boolean) | Αντιπροσωπεύει τα σημεία εκτός ορίων. Αληθές αν τα σημεία εκτός ορίων εμφανίζονται στο διάγραμμα BoxAndWhisker. Εφαρμόζεται μόνο σε διαγράμματα BoxAndWhisker. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setSmooth {#setSmooth}

| Όνομα | Περιγραφή |
| --- | --- |
| setSmooth (boolean) | Αντιπροσωπεύει την εξομάλυνση καμπύλης. Αληθές αν η εξομάλυνση καμπύλης ενεργοποιείται για το διάγραμμα γραμμής ή το διάγραμμα scatter. Εφαρμόζεται μόνο σε διαγράμματα γραμμής και scatter που συνδέονται με γραμμές. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setType {#setType}

| Όνομα | Περιγραφή |
| --- | --- |
| setType (int) | Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/Εγγραφή ChartType. |

**Επιστρέφει:**
void

---