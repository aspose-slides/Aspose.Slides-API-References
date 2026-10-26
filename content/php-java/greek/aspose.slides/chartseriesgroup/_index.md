---
title: ChartSeriesGroup
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/chartseriesgroup/
---
## ChartSeriesGroup κλάση

Αναπαριστά μια ομάδα σειρών.

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup.
2) Η ομάδα σειρών περιέχει κάποιες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»).
«Ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι Ανάγνωση/Εγγραφή.
Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| Name | Description |
| --- | --- |
| getBubbleSizeRepresentation () | Καθορίζει πώς οι τιμές μεγέθους φούσκας παρουσιάζονται στο γράφημα φούσκας. Ανάγνωση/Εγγραφή BubbleSizeRepresentationType. |

**Επιστρέφει:**
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| Name | Description |
| --- | --- |
| getBubbleSizeScale () | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φούσκας (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
int


---


### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση IChart. |

**Επιστρέφει:**
[Chart](../chart)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| Name | Description |
| --- | --- |
| getDoughnutHoleSize () | Καθορίζει το μέγεθος του κεντρικού οπού σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
byte


---


### getFirstSliceAngle {#getFirstSliceAngle}

| Name | Description |
| --- | --- |
| getFirstSliceAngle () | Αποκτά ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, σε μοίρες (δευτερόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
int


---


### getGapDepth {#getGapDepth}

| Name | Description |
| --- | --- |
| getGapDepth () | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε γράφημα 3D. Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
int


---


### getGapWidth {#getGapWidth}

| Name | Description |
| --- | --- |
| getGapWidth () | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
int


---


### getHiLowLinesFormat {#getHiLowLinesFormat}

| Name | Description |
| --- | --- |
| getHiLowLinesFormat () | Καθορίζει τη μορφή HiLowLines. Οι HiLowLines εφαρμόζονται στους τύπους γραφήματος HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |

**Επιστρέφει:**
[ChartLinesFormat](../chartlinesformat)


---


### getOverlap {#getOverlap}

| Name | Description |
| --- | --- |
| getOverlap () | Καθορίζει το πόσο οι ράβδοι και οι στήλες θα επικαλύπτονται σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο διάστημα (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή διάστημα. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως μεταξύ τους). Αυτή η ιδιότητα είναι Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
byte

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Εκτυπώνεται όταν η τιμή ορίζεται εκτός του έγκυρου εύρους -100 έως 100. |


---


### getPieSplitBy {#getPieSplitBy}

| Name | Description |
| --- | --- |
| getPieSplitBy () | Καθορίζει πώς προσδιορίζονται τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας. Ανάγνωση/Εγγραφή PieSplitType. |

**Επιστρέφει:**
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| Name | Description |
| --- | --- |
| getPieSplitCustomPoints () | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα γράφημα πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας με προσαρμοσμένη διαίρεση. Περιέχει τα σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ραβδό σε ένα γράφημα πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας. Μόνο για ανάγνωση PieSplitCustomPointCollection. |

**Επιστρέφει:**
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| Name | Description |
| --- | --- |
| getPieSplitPosition () | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ραβδό σε ένα γράφημα πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| Name | Description |
| --- | --- |
| getPlotOnSecondAxis () | Δείχνει αν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση IPresentation. |

**Επιστρέφει:**
[Presentation](../presentation)


---


### getSecondPieSize {#getSecondPieSize}

| Name | Description |
| --- | --- |
| getSecondPieSize () | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου ενός γράφηματος πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
int


---


### getSeries {#getSeries}

| Name | Description |
| --- | --- |
| getSeries () | Επιστρέφει μια συλλογή σειρών. Μόνο για ανάγνωση IChartSeriesReadonlyCollection. |

**Επιστρέφει:**
ChartSeriesReadonlyCollection


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση BaseSlide. |

**Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση CombinableSeriesTypesGroup. |

**Επιστρέφει:**
int


---


### getUpDownBars {#getUpDownBars}

| Name | Description |
| --- | --- |
| getUpDownBars () | Παρέχει πρόσβαση στα up/down bars γραφήματος γραμμής ή μετοχών. Μόνο για ανάγνωση IUpDownBarsManager. |

**Επιστρέφει:**
[UpDownBarsManager](../updownbarsmanager)


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Αποκτά το στοιχείο στο συγκεκριμένο δείκτη. |

**Επιστρέφει:**
[ChartSeries](../chartseries)


---


### hasSeriesLines {#hasSeriesLines}

| Name | Description |
| --- | --- |
| hasSeriesLines () | Αληθές αν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβα γραμμών και πίτες OfPie. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean


---


### isColorVaried {#isColorVaried}

| Name | Description |
| --- | --- |
| isColorVaried () | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean


---


### setBubbleSizeRepresentation {#setBubbleSizeRepresentation}

| Name | Description |
| --- | --- |
| setBubbleSizeRepresentation (int) | Καθορίζει πώς οι τιμές μεγέθους φούσκας παρουσιάζονται στο γράφημα φούσκας. Ανάγνωση/Εγγραφή BubbleSizeRepresentationType. |

**Επιστρέφει:**
void


---


### setBubbleSizeScale {#setBubbleSizeScale}

| Name | Description |
| --- | --- |
| setBubbleSizeScale (int) | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φούσκας (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void


---


### setColorVaried {#setColorVaried}

| Name | Description |
| --- | --- |
| setColorVaried (boolean) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void


---


### setDoughnutHoleSize {#setDoughnutHoleSize}

| Name | Description |
| --- | --- |
| setDoughnutHoleSize (byte) | Καθορίζει το μέγεθος του κεντρικού οπού σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
void


---


### setFirstSliceAngle {#setFirstSliceAngle}

| Name | Description |
| --- | --- |
| setFirstSliceAngle (int) | Αποκτά ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, σε μοίρες (δευτερόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void


---


### setGapDepth {#setGapDepth}

| Name | Description |
| --- | --- |
| setGapDepth (int) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε γράφημα 3D. Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void


---


### setGapWidth {#setGapWidth}

| Name | Description |
| --- | --- |
| setGapWidth (int) | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void


---


### setOverlap {#setOverlap}

| Name | Description |
| --- | --- |
| setOverlap (byte) | Καθορίζει το πόσο οι ράβδοι και οι στήλες θα επικαλύπτονται σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο διάστημα (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή διάστημα. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως μεταξύ τους). Αυτή η ιδιότητα είναι Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Εκτυπώνεται όταν η τιμή ορίζεται εκτός του έγκυρου εύρους -100 έως 100. |


---


### setPieSplitBy {#setPieSplitBy}

| Name | Description |
| --- | --- |
| setPieSplitBy (int) | Καθορίζει πώς προσδιορίζονται τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας. Ανάγνωση/Εγγραφή PieSplitType. |

**Επιστρέφει:**
void


---


### setPieSplitPosition {#setPieSplitPosition}

| Name | Description |
| --- | --- |
| setPieSplitPosition (double) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ραβδό σε ένα γράφημα πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
void


---


### setSecondPieSize {#setSecondPieSize}

| Name | Description |
| --- | --- |
| setSecondPieSize (int) | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου ενός γράφηματος πίτας-μέσα-πίτας ή ράβδου-μέσα-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/Εγγραφή int. |

**Επιστρέφει:**
void


---


### setSeriesLines {#setSeriesLines}

| Name | Description |
| --- | --- |
| setSeriesLines (boolean) | Αληθές αν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβα γραμμών και πίτες OfPie. Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void


---