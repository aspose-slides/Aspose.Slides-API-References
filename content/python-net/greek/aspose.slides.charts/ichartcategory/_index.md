---
title: IChartCategory class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/ichartcategory/
---
## IChartCategory κλάση

Αντιπροσωπεύει τις κατηγορίες διαγραμμάτων.

Ο τύπος IChartCategory εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`use_cell`](/slides/python-net/el/aspose.slides.charts/ichartcategory/use_cell/) | Εάν είναι true τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για <br/>            την αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει κατηγορία πολλαπλών επιπέδων).<br/>            Εάν είναι false τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται <br/>            για την αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων).<br/>            Μόνο ανάγνωση **bool**. |
| [`as_cell`](/slides/python-net/el/aspose.slides.charts/ichartcategory/as_cell/) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell.<br/>            Εάν η κατηγορία είναι πολλαπλού επιπέδου τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0".<br/>            Ανάγνωση/εγγραφή [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/el/aspose.slides.charts/ichartcategory/as_literal/) | Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`value`](/slides/python-net/el/aspose.slides.charts/ichartcategory/value/) | Εάν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value.<br/>            Εάν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`cached_value`](/slides/python-net/el/aspose.slides.charts/ichartcategory/cached_value/) | Αποκτά την αποθηκευμένη τιμή μιας κατηγορίας διαγράμματος.<br/>            Μόνο ανάγνωση [`ICachedChartValue`](/slides/python-net/el/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/el/aspose.slides.charts/ichartcategory/grouping_levels/) | Διαχειριζόμενο δοχείο των τιμών των επιπέδων ομαδοποίησης κατηγοριών διαγράμματος.<br/>            Η κατηγορία πολλαπλών επιπέδων περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης.<br/>            Η αρίθμηση των επιπέδων ομαδοποίησης είναι μηδενική.<br/>            Μόνο ανάγνωση [`IChartCategoryLevelsManager`](/slides/python-net/el/aspose.slides.charts/ichartcategorylevelsmanager). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`remove(self)`](/slides/python-net/el/aspose.slides.charts/ichartcategory/remove/#) | Αφαιρεί την κατηγορία από το διάγραμμα. |


### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)