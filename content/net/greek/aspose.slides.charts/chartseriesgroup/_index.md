---
title: ChartSeriesGroup
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ομάδα σειρών.
type: docs
weight: 1470
url: /el/aspose.slides.charts/chartseriesgroup/
---
## Κλάση ChartSeriesGroup

Αναπαριστά μια ομάδα σειρών.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Καθορίζει πώς αντιπροσωπεύονται οι τιμές του μεγέθους φυσαλίδας στο γράφημα φυσαλίδων. Ανάγνωση/Εγγραφή [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Καθορίζει τον παράγοντα κλίμακας για το γράφημα φυσαλίδων (μπορεί να βρίσκεται μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/Εγγραφή Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/Εγγραφή Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). Ανάγνωση/Εγγραφή UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε γράφημα 3Δ, ως ποσοστό του πλάτους του δείκτη. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/Εγγραφή UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Λαμβάνει ή ορίζει το διάκενο μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/Εγγραφή UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Αληθές εάν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβακτες ράβδους και γραφήματα OfPie. Ανάγνωση/Εγγραφή Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Καθορίζει τη μορφή HiLowLines. HiLowLines εφαρμόζεται με τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/Εγγραφή Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Καθορίζει το πόσο οι ράβδοι και οι στήλες θα επικαλύπτονται σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο διάστημα (οι ράβδοι είναι πλήρως χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή διάστημα. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Ανάγνωση/Εγγραφή [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Μόνο για ανάγνωση [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/Εγγραφή Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Δείχνει εάν οι σειρές αυτής της ομάδας απεικονίζονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε γράφημα pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/Εγγραφή UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Επιστρέφει μια συλλογή σειρών. Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Παρέχει πρόσβαση στις γραμμές ανοδικών/καθοδικών της γραμμής ή του γραφήματος μετοχών. Μόνο για ανάγνωση [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Σχόλια

1) Δείτε τη σύνοψη και τα σχόλια για την κλάση ChartSeriesGroupCollection και την απαρίθμηση CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειράς που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

### Δείτε επίσης

* διασύνδεση [IChartSeriesGroup](../ichartseriesgroup)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* σύνθεση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->