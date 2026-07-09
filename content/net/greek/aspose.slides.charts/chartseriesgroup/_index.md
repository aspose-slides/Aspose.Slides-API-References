---
title: ChartSeriesGroup
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ομάδα σειρών.
type: docs
weight: 1460
url: /el/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup κλάση

Αντιπροσωπεύει ομάδα σειρών.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας παρουσιάζονται στο γράφημα φυσαλίδων. Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 % του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Καθορίζει το μέγεθος του κεντρικού σκορ σε γράφημα δαχτυλίδι (μπορεί να είναι μεταξύ 0 και 90 % του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Λαμβάνει ή ορίζει τη γωνία της πρώτης φέτας ή δαχτυλιδιού, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3D γράφημα. Ανάγνωση/εγγραφή UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Καθορίζει το κενό μεταξύ ομάδων ραβδών ή στηλών, ως ποσοστό του πλάτους της ραβδού ή της στήλης. Ανάγνωση/εγγραφή UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Αληθές εάν το γράφημα περιέχει γραμμές σειράς. Εφαρμόζεται σε γραφήματα στοιβασμένων ραβδών και OfPie. Ανάγνωση/εγγραφή Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Καθορίζει τη μορφή HiLowLines. Οι HiLowLines εφαρμόζονται με τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Καθορίζει το πόσο οι ράβδοι και οι στήλες θα επικαλύπτονται σε 2-Δ γράφημα, ως ποσοστό (από -100 % έως 100 %). -100 %: Μέγιστο κενό (οι ράβδοι είναι εντελώς χωρισμένες). 0 %: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή κενό. 100 %: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Καθορίζει πώς θα προσδιορίζονται ποια σημεία δεδομένων βρίσκονται στο δεύτερο κομμάτι σε γράφημα πίτας-πίτας ή ράβδου-πίτας. Ανάγνωση/εγγραφή [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για γράφημα πίτας-πίτας ή ράβδου-πίτας με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στο δεύτερο κομμάτι. Μόνο για ανάγνωση [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Καθορίζει τιμή που θα χρησιμοποιηθεί για τον καθορισμό ποια σημεία δεδομένων βρίσκονται στο δεύτερο κομμάτι σε γράφημα πίτας-πίτας ή ραβδό-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Καθορίζει εάν οι σειρές αυτής της ομάδας προβάλλονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Καθορίζει το μέγεθος του δεύτερου κομματιού ή ράβδου σε γράφημα πίτας-πίτας ή ράβδου-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 %). Ανάγνωση/εγγραφή UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Επιστρέφει μια συλλογή σειρών. Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Επιστρέφει τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Παρέχει πρόσβαση σε γραμμές πάνω/κάτω διαγράμματος γραμμής ή μετοχών. Μόνο για ανάγνωση [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Παρατηρήσεις

1) Δείτε την περίληψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και την απαρίθμηση CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### Δείτε επίσης

* διασύνδεση [IChartSeriesGroup](../ichartseriesgroup)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->