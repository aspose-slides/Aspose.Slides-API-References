---
title: IChartSeriesGroup class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup κλάση

Αναπαριστά ομάδα σειρών.

Ο τύπος IChartSeriesGroup εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`type`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/type/) | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών.<br/>            Μόνο ανάγνωση [`CombinableSeriesTypesGroup`](/slides/python-net/el/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Υποδεικνύει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα.<br/>            Μόνο ανάγνωση **bool**. |
| [`series`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/series/) | Επιστρέφει μια συλλογή μόνο για ανάγνωση από σειρές διαγράμματος.<br/>            Μόνο ανάγνωση [`IChartSeriesReadonlyCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Παρέχει πρόσβαση σε γραμμές πάνω/κάτω των γραμμικών ή χάρτη αποθέματος.<br/>            Μόνο ανάγνωση [`IUpDownBarsManager`](/slides/python-net/el/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/gap_width/) | Λαμβάνει ή ορίζει το διάστημα μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης.<br/>            Η τιμή πρέπει να είναι μεταξύ 0 και 500.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`gap_depth`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε 3Δ διάγραμμα, ως ποσοστό του πλάτους του δείκτη.<br/>            Η τιμή πρέπει να είναι μεταξύ 0 και 500.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`first_slice_angle`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου, <br/>            σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`is_color_varied`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`has_series_lines`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Αληθές εάν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε διαγράμματα στην στοίβα των ράβδων και OfPie.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`overlap`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/overlap/) | Καθορίζει πόσο θα επικαλύπτονται οι ράβδοι και στήλες σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%).<br/>             - -100%: Μέγιστο κενό (οι ράβδοι είναι εντελώς χωρισμένες).<br/>             - 0%: Οι ράβδοι τοποθετούνται δίπλα-δίπλα χωρίς επικάλυψη ή κενό.<br/>             - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως).<br/>             Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή **int**. |
| [`second_pie_size`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Καθορίζει το μέγεθος του δεύτερου κομματιού ή ράβδου σε διάγραμμα πίτα-εντός-πίτας ή ράβδο-εντός-πίτας, ως ποσοστό του μεγέθους του πρώτου κομματιού (μπορεί <br/>            να είναι μεταξύ 5 και 200 τοις εκατό).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`pie_split_position`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιορίσει ποια σημεία δεδομένων <br/>            βρίσκονται στο δεύτερο κομμάτι ή ράβδο σε διάγραμμα πίτα-εντός-πίτας ή ράβδο-εντός-πίτας.<br/>            Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`pie_split_by`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Καθορίζει πώς θα προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στο δεύτερο κομμάτι ή ράβδο <br/>            σε διάγραμμα πίτα-εντός-πίτας ή ράβδο-εντός-πίτας.<br/>            Ανάγνωση/εγγραφή [`PieSplitType`](/slides/python-net/el/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα πίτα-εντός-πίτας ή ράβδο-εντός-πίτας με προσαρμοσμένη διαίρεση.<br/>            Περιέχει σημεία δεδομένων που θα σχεδιαστούν στο δεύτερο κομμάτι ή ράβδο σε διάγραμμα πίτα-εντός-πίτας ή <br/>            ράβδο-εντός-πίτας.<br/>            Μόνο ανάγνωση [`IPieSplitCustomPointCollection`](/slides/python-net/el/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό <br/>            του μεγέθους της περιοχής σχεδίασης).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`bubble_size_scale`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι <br/>            μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`hi_low_lines_format`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Καθορίζει τη μορφή HiLowLines.<br/>            HiLowLines εφαρμόζεται με τους τύπους διαγράμματος HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Καθορίζει πώς θα παριστώνται οι τιμές μεγέθους φυσαλίδων στο διάγραμμα φυσαλίδων.<br/>            Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](/slides/python-net/el/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Λαμβάνει το στοιχείο στο καθορισμένο δείκτη.

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Σχόλια

1) Δείτε την σύνοψη και τα σχόλια για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup.  
2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα ("ιδιότητες ομάδας σειρών").  
   "Ιδιότητες ομάδας σειρών" στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή.  
   Κάθε μια από τις "ιδιότητες ομάδας σειρών" μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)