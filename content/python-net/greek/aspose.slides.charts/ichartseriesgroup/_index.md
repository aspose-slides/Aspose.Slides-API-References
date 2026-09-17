---
title: IChartSeriesGroup class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup κλάση

Αναπαριστά ομάδα σειρών.

Ο τύπος IChartSeriesGroup εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`type`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/type/) | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών.<br/>            Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](/slides/python-net/el/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Δείχνει αν οι σειρές αυτής της ομάδας εμφανίζονται σε δευτερεύοντα άξονα.<br/>            Μόνο για ανάγνωση **bool**. |
| [`series`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/series/) | Επιστρέφει μια συλλογή μόνο για ανάγνωση των σειρών γραφήματος.<br/>            Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Παρέχει πρόσβαση σε ράβδους άνω/κάτω γραφήματος Line ή Stock.<br/>            Μόνο για ανάγνωση [`IUpDownBarsManager`](/slides/python-net/el/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/gap_width/) | Καθορίζει το διάστημα μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδους ή στήλης.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`gap_depth`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του σημειωτή, μεταξύ των σειρών δεδομένων σε γράφημα 3D.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`first_slice_angle`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος σε πίτα ή δακτύλιο γραφήματος, <br/>            σε μοίρες (δεξιόστροφα από την πάνω, από 0 έως 360 μοίρες).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`is_color_varied`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Καθορίζει ότι κάθε σημειωτής δεδομένων στη σειρά έχει διαφορετικό χρώμα.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`has_series_lines`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Αληθές εάν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβαγμα ράβδων και γραφήματα OfPie.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`overlap`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/overlap/) | Καθορίζει το πόσο οι ράβδοι και στήλες θα επικαλύπτονται σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%).<br/>             - -100%: Μέγιστο κενό (οι ράβδοι είναι εντελώς χωρισμένοι).<br/>             - 0%: Οι ράβδοι τοποθετούνται δίπλα-δίπλα χωρίς επικάλυψη ή κενό.<br/>             - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως).<br/>             Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή **int**. |
| [`second_pie_size`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου ενός γραφήματος pie-of-pie ή <br/>            ενός γραφήματος bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί <br/>            να είναι μεταξύ 5 και 200 τοις εκατό).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`pie_split_position`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων <br/>            που βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. <br/>            Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`pie_split_by`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο <br/>            σε γράφημα pie-of-pie ή bar-of-pie.<br/>            Ανάγνωση/εγγραφή [`PieSplitType`](/slides/python-net/el/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένο διαχωρισμό.<br/>            Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο σε ένα γράφημα pie-of-pie ή <br/>            bar-of-pie.<br/>            Μόνο για ανάγνωση [`IPieSplitCustomPointCollection`](/slides/python-net/el/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό <br/>            του μεγέθους της περιοχής σχεδίασης).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`bubble_size_scale`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι <br/>            μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους).<br/>            Ανάγνωση/εγγραφή **int**. |
| [`hi_low_lines_format`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Καθορίζει τη μορφή HiLowLines. <br/>            HiLowLines εφαρμόζεται με τους τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Καθορίζει πώς οι τιμές μεγέθους φυσαλίδων αντιπροσωπεύονται στο γράφημα φυσαλίδων.<br/>            Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](/slides/python-net/el/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Λαμβάνει το στοιχείο στη συγκεκριμένη θέση.

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Παρατηρήσεις

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και την απαρίθμηση CombinableSeriesTypesGroup.
2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειράς που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)