---
title: ChartCategory class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartcategory/
---
## ChartCategory κλάση

Αντιπροσωπεύει τις κατηγορίες διαγράμματος.

Ο τύπος ChartCategory εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`use_cell`](/slides/python-net/el/aspose.slides.charts/chartcategory/use_cell/) | Εάν είναι true τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για <br/>            αποθήκευση της κατηγορίας ( αυτή η περίπτωση υποστηρίζει μια κατηγορία πολλαπλών επιπέδων ).<br/>            Εάν είναι false τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται <br/>            για αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων).<br/>            Μόνο για ανάγνωση **bool**. |
| [`as_cell`](/slides/python-net/el/aspose.slides.charts/chartcategory/as_cell/) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell.<br/>            Εάν η κατηγορία είναι πολλαπλών επιπέδων τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0".<br/>            Ανάγνωση/εγγραφή [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/el/aspose.slides.charts/chartcategory/as_literal/) | Επιστρέφει ή ορίζει το αντικείμενο AsLiteral.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`value`](/slides/python-net/el/aspose.slides.charts/chartcategory/value/) | Εάν UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value.<br/>            Εάν UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`grouping_levels`](/slides/python-net/el/aspose.slides.charts/chartcategory/grouping_levels/) | Διαχειριζόμενος κοντέινερ των τιμών των επιπέδων ομαδοποίησης κατηγοριών διαγράμματος.<br/>            Η κατηγορία πολλαπλών επιπέδων περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης.<br/>            Η αρίθμηση των επιπέδων ομαδοποίησης είναι μηδενική.<br/>            Μόνο για ανάγνωση [`IChartCategoryLevelsManager`](/slides/python-net/el/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/el/aspose.slides.charts/chartcategory/cached_value/) | Αποκτά την αποθηκευμένη τιμή μιας κατηγορίας διαγράμματος.<br/>            Μόνο για ανάγνωση [`ICachedChartValue`](/slides/python-net/el/aspose.slides.charts/icachedchartvalue). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`remove(self)`](/slides/python-net/el/aspose.slides.charts/chartcategory/remove/#) | Αφαιρεί την κατηγορία από το διάγραμμα. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)