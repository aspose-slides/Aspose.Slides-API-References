---
title: IChartData class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/
---
## IChartData κλάση

Αντιπροσωπεύει τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση γραφήματος.

Ο τύπος IChartData εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/el/aspose.slides.charts/ichartdata/chart_data_workbook/) | Παρέχει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες γραφήματος.<br/>            Μόνο ανάγνωση [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/el/aspose.slides.charts/ichartdata/series/) | Παρέχει τις σειρές.<br/>            Μόνο ανάγνωση [`IChartSeriesCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/el/aspose.slides.charts/ichartdata/series_groups/) | Παρέχει τις ομάδες σειρών.<br/>            Μόνο ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/categories/) | Παρέχει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες <br/>            εάν η ιδιότητα [`IChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/use_secondary_categories) είναι ψευδής).<br/>            Μόνο ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/use_secondary_categories/) | Εάν είναι ψευδές, τότε η ιδιότητα [`IChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/secondary_categories) επιστρέφει None και τα δεδομένα <br/>            στην ιδιότητα [`IChartData.categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/categories) χρησιμοποιούνται και για τις κύριες και τις δευτερεύουσες σειρές.<br/>            Εάν είναι αληθές, τότε τα δεδομένα στην ιδιότητα [`IChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/secondary_categories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα <br/>            στην ιδιότητα [`IChartData.categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/categories) χρησιμοποιούνται για τις κύριες σειρές.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/secondary_categories/) | Παρέχει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα [`IChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/use_secondary_categories) είναι αληθής.<br/>            Μόνο ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/el/aspose.slides.charts/ichartdata/data_source_type/) | Αντιπροσωπεύει την πηγή δεδομένων του γραφήματος |
| [`external_workbook_path`](/slides/python-net/el/aspose.slides.charts/ichartdata/external_workbook_path/) | Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλιοθήκης εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά None |
| [`embedded_workbook_type`](/slides/python-net/el/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Παρέχει τον τύπο του ενσωματωμένου βιβλιοθήκης εργασίας.<br/>            Επιστρέφει [`WorkbookType.NOT_DEFINED`](/slides/python-net/el/aspose.slides.charts/workbooktype/NOT_DEFINED) εάν το [`IChartData.data_source_type`](/slides/python-net/el/aspose.slides.charts/ichartdata/data_source_type) είναι <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/el/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Μόνο ανάγνωση [`WorkbookType`](/slides/python-net/el/aspose.slides.charts/workbooktype). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/el/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Ορίζει εξωτερική βιβλιοθήκη εργασίας ως πηγή δεδομένων για το γράφημα. Τα δεδομένα του γραφήματος θα ενημερωθούν από την προορισμένη βιβλιοθήκη εργασίας. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/el/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Ορίζει εξωτερική βιβλιοθήκη εργασίας ως πηγή δεδομένων για το γράφημα. |
| [`read_workbook_stream(self)`](/slides/python-net/el/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Γράφει το εσωτερικά περιλαμβανόμενο βιβλίο εργασίας Excel σε ροή μνήμης. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/el/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Αρχικοποιεί το εσωτερικά περιλαμβανόμενο βιβλίο εργασίας Excel με την τιμή που καθορίζεται από το χρήστη. |
| [`set_range(self, formula)`](/slides/python-net/el/aspose.slides.charts/ichartdata/set_range/#str) | Ορίζει το εύρος δεδομένων του γραφήματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν με βάση το νέο εύρος δεδομένων.<br/>            Εάν ο αριθμός των σειρών στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό των σειρών στα δεδομένα του γραφήματος, τότε επιπλέον σειρές με τον ίδιο τύπο<br/>            όπως η τελευταία σειρά στην τρέχουσα συλλογή, θα προστεθούν στο τέλος της συλλογής. |
| [`get_range(self)`](/slides/python-net/el/aspose.slides.charts/ichartdata/get_range/#) | Παρέχει το εύρος δεδομένων του γραφήματος. |
| [`switch_row_column(self)`](/slides/python-net/el/aspose.slides.charts/ichartdata/switch_row_column/#) | Ανταλλάσσει τα δεδομένα πάνω στον άξονα.<br/>            Τα δεδομένα που απεικονίζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)