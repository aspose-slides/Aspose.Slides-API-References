---
title: ErrorBarsFormat class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat κλάση

Αναπαριστά τις γραμμές σφάλματος των σειρών διαγραμμάτων. Προσαρμοσμένες τιμές ErrorBars βρίσκονται στο IChartDataPointCollection (στην ιδιότητα [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/el/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Ο τύπος ErrorBarsFormat εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`type`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/type/) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος.<br/>            Ανάγνωση/εγγραφή [`ErrorBarType`](/slides/python-net/el/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/value_type/) | Αναπαριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος.<br/>            Σε περίπτωση τύπου προσαρμοσμένης τιμής, για να ορίσετε τιμή χρησιμοποιήστε την ιδιότητα [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/el/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς.<br/>            Σε περίπτωση τύπου Fixed, Percentage ή StandardDeviation, χρησιμοποιήστε την ιδιότητα Value για να ορίσετε τιμή.<br/>            Ανάγνωση/εγγραφή [`ErrorBarValueType`](/slides/python-net/el/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/has_end_cap/) | Καθορίζει ότι δεν σχεδιάζεται άκρο στην γραμμή σφάλματος.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`value`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/value/) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τους τύπους Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος.<br/>            Σε οποιαδήποτε άλλη περίπτωση θα επιστρέψει NaN.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`format`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/format/) | Αναπαριστά τη μορφή των γραμμών σφάλματος.<br/>            Ανάγνωση/εγγραφή [`IFormat`](/slides/python-net/el/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/chart/) | Επιστρέφει το γονικό διάγραμμα.<br/>            Μόνο ανάγνωση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/is_visible/) | Λαμβάνει ή ορίζει τη ορατότητα των Error Bars.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`slide`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)