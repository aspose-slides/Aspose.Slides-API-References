---
title: ChartSeriesGroup class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup κλάση

Αντιπροσωπεύει μια ομάδα σειρών.

Ο τύπος ChartSeriesGroup εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`type`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/type/) | Επιστρέφει τον τύπο αυτής της ομάδας σειρών.<br/>            Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](/slides/python-net/el/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Δείχνει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα.<br/>            Μόνο για ανάγνωση **bool**. |
| [`series`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/series/) | Επιστρέφει μια συλλογή σειρών.<br/>            Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Παρέχει πρόσβαση σε μπαρ ανόδου/κάθισης των διαγραμμάτων Γραμμής ή Απόθεσης.<br/>            Μόνο για ανάγνωση [`IUpDownBarsManager`](/slides/python-net/el/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/gap_width/) | Λαμβάνει ή ορίζει το διάστημα μεταξύ ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης.<br/>            Η τιμή πρέπει να είναι μεταξύ 0 και 500.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`gap_depth`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/gap_depth/) | Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε 3D διάγραμμα, ως ποσοστό του πλάτους του δείκτη.<br/>            Η τιμή πρέπει να είναι μεταξύ 0 και 500.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`first_slice_angle`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, <br/>            σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`doughnut_hole_size`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό <br/>            του μεγέθους της περιοχής σχεδίασης).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`overlap`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/overlap/) | Καθορίζει πόσο θα επικαλύπτονται μπαρ και στήλες σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%).<br/>             - -100%: Μέγιστο διάστημα (τα μπαρ είναι εντελώς διαχωρισμένα).<br/>             - 0%: Τα μπαρ τοποθετούνται πλάι-πλαϊνά χωρίς επικάλυψη ή διάστημα.<br/>             - 100%: Μέγιστη επικάλυψη (τα μπαρ επικαλύπτονται πλήρως).<br/>             Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή **int**. |
| [`second_pie_size`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Καθορίζει το μέγεθος του δεύτερου τμήματος πίτας ή μπαρ σε διάγραμμα πίτας-εντός-πίτας ή <br/>            μπαρ-εντός-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί <br/>            να είναι μεταξύ 5 και 200 τοις εκατό).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`bubble_size_representation`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φυσαλίδων σε διάγραμμα φυσαλίδων.<br/>            Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](/slides/python-net/el/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον καθορισμό των σημείων δεδομένων <br/>            που βρίσκονται στο δεύτερο τμήμα πίτας ή μπαρ σε διάγραμμα πίτας-εντός-πίτας ή μπαρ-εντός-πίτας. <br/>            Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`pie_split_by`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που είναι στο δεύτερο τμήμα πίτας ή μπαρ <br/>            σε διάγραμμα πίτας-εντός-πίτας ή μπαρ-εντός-πίτας.<br/>            Ανάγνωση/εγγραφή [`PieSplitType`](/slides/python-net/el/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`has_series_lines`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Αληθές εάν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε στηματοποιημένα μπαρ και διαγράμματα OfPie.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`hi_low_lines_format`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Καθορίζει τη μορφή HiLowLines. <br/>            HiLowLines εφαρμόζεται με τους τύπους διαγραμμάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι <br/>            μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`pie_split_custom_points`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα πίτας-εντός-πίτας ή μπαρ-εντός-πίτας με προσαρμοσμένη διαίρεση.<br/>            Περιέχει τα σημεία δεδομένων που θα σχεδιαστούν στο δεύτερο τμήμα πίτας ή μπαρ σε ένα διάγραμμα πίτας-εντός-πίτας ή <br/>            μπαρ-εντός-πίτας.<br/>            Μόνο για ανάγνωση [`PieSplitCustomPointCollection`](/slides/python-net/el/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/chart/) | Επιστρέφει το γονικό διάγραμμα.<br/>            Μόνο για ανάγνωση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Παρατηρήσεις

1) Δείτε την περίληψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup.
2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»).
«Ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή.
Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)