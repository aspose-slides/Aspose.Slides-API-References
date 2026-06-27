---
title: ChartSeriesGroup
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια ομάδα σειρών.
type: docs
weight: 1440
url: /el/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup κλάση

Αντιπροσωπεύει μια ομάδα σειρών.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φυσαλίδας στο διάγραμμα φυσαλίδων. Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Καθορίζει το μέγεθος της κεντρικής τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Αποκτά ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από το επάνω, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Αποκτά ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε τρισδιάστατο διάγραμμα. Ανάγνωση/εγγραφή UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Καθορίζει το κενό μεταξύ ομάδων ραβδών ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/εγγραφή UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Αληθές εάν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβακτες μπαρ και διαγράμματα OfPie. Ανάγνωση/εγγραφή Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Καθορίζει τη μορφή HiLowLines. Η HiLowLines εφαρμόζεται με τους τύπους διαγράμματος HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Αποκτά το στοιχείο στο καθορισμένο δείκτη. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Καθορίζει το πόσο θα υπερκαλύπτανται οι ράβδοι και οι στήλες σε διαγράμματα 2-Δ, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο κενό (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή κενό. - 100%: Μέγιστη επικάλυψη (οι ράβδοι καλύπτουν πλήρως η μία την άλλη). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα pie-of-pie ή bar-of-pie. Ανάγνωση/εγγραφή [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Προσαρμοσμένες πληροφορίες διαχωρισμού για διάγραμμα pie-of-pie ή bar-of-pie με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο σε ένα διάγραμμα pie-of-pie ή bar-of-pie. Μόνο για ανάγνωση [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Δείχνει εάν οι σειρές αυτής της ομάδας απεικονίζονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου ενός διαγράμματος pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/εγγραφή UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Επιστρέφει μια συλλογή σειρών. Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Παρέχει πρόσβαση σε μπροστινά/οπίσθια bars διαγραμμάτων Line ή Stock. Μόνο για ανάγνωση [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Παρατηρήσεις

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειράς»). Οι «ιδιότητες ομάδας σειράς» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειράς» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### Δείτε επίσης

* διεπαφή [IChartSeriesGroup](../ichartseriesgroup)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->