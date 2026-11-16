---
title: IChartSeriesGroup
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ομάδα σειρών.
type: docs
weight: 1970
url: /el/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup διασύνδεση

Αντιπροσωπεύει μια ομάδα σειρών.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Επιτρέπει την απόκτηση της βασικής διασύνδεσης IChartComponent. Μόνο για ανάγνωση [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φυσαλίδων στο γράφημα φυσαλίδων. Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Καθορίζει το συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Καθορίζει το μέγεθος της τρύπας σε γράφημα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δαχτυλιδιού, σε μοίρες (δεξιόστροφα από το πάνω, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε ένα 3D γράφημα, ως ποσοστό του πλάτους του δείκτη. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/εγγραφή UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Λαμβάνει ή ορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/εγγραφή UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Αληθές εάν το γράφημα περιέχει γραμμές σειράς. Εφαρμόζεται σε γραφήματα στοίβαγμένων ραβδών και OfPie. Ανάγνωση/εγγραφή Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Καθορίζει τη μορφή HiLowLines. Οι HiLowLines εφαρμόζονται με τους τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Καθορίζει το πόσο θέλουν οι ράβδοι και οι στήλες να επικαλύπτονται σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστη απόσταση (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται δίπλα-δίπλα χωρίς επικάλυψη ή απόσταση. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Καθορίζει πώς προσδιορίζεται ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ραβδό σε γράφημα pie-of-pie ή bar-of-pie. Ανάγνωση/εγγραφή [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένη διαίρεση. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ραβδό σε ένα γράφημα pie-of-pie ή bar-of-pie. Μόνο για ανάγνωση [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ραβδό σε γράφημα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Δείχνει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερή άξονα. Μόνο για ανάγνωση Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Καθορίζει το μέγεθος της δεύτερης πίτας ή ραβδό ενός γράφηματος pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/εγγραφή UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Επιστρέφει μια μόνο για ανάγνωση συλλογή σειρών γραφήματος. Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Παρέχει πρόσβαση στις γραμμές ανοδικής/καθοδικής τιμής ενός γραφήματος γραμμής ή μετοχών. Μόνο για ανάγνωση [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Παρατηρήσεις

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες "ιδιότητες ομάδας σειρών" που είναι κοινές για κάθε σειρά στην ομάδα. Οι "ιδιότητες ομάδας σειρών" στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις "ιδιότητες ομάδας σειρών" μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

### Δείτε επίσης

* διασύνδεση [IChartComponent](../ichartcomponent)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->