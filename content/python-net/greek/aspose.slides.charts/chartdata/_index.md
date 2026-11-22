---
title: ChartData class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/
---
## ChartData κλάση

Αναπαριστά δεδομένα που χρησιμοποιούνται για την αποτύπωση ενός διαγράμματος.

Ο τύπος ChartData εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/el/aspose.slides.charts/chartdata/chart_data_workbook/) | Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος.<br/>            Μόνο-ανάγνωση [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/el/aspose.slides.charts/chartdata/series/) | Λαμβάνει τις σειρές.<br/>            Μόνο-ανάγνωση [`IChartSeriesCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/el/aspose.slides.charts/chartdata/series_groups/) | Λαμβάνει τις ομάδες των σειρών.<br/>            Μόνο-ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories/) | Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες <br/>            εάν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι ψευδής).<br/>            Μόνο-ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories/) | Εάν είναι ψευδής, τότε η ιδιότητα [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) επιστρέφει None και τα δεδομένα <br/>            στην ιδιότητα [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές.<br/>            Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα <br/>            στην ιδιότητα [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) χρησιμοποιούνται για κύριες σειρές.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories/) | Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι αληθής.<br/>            Μόνο-ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/el/aspose.slides.charts/chartdata/data_source_type/) | Καθορίζει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, αλλιώς None |
| [`external_workbook_path`](/slides/python-net/el/aspose.slides.charts/chartdata/external_workbook_path/) | Καθορίζει την πηγή δεδομένων του διαγράμματος |
| [`embedded_workbook_type`](/slides/python-net/el/aspose.slides.charts/chartdata/embedded_workbook_type/) | Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας.<br/>            Επιστρέφει [`WorkbookType.NOT_DEFINED`](/slides/python-net/el/aspose.slides.charts/workbooktype/NOT_DEFINED) εάν το [`ChartData.data_source_type`](/slides/python-net/el/aspose.slides.charts/chartdata/data_source_type) είναι <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/el/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Μόνο-ανάγνωση [`WorkbookType`](/slides/python-net/el/aspose.slides.charts/workbooktype). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/el/aspose.slides.charts/chartdata/set_external_workbook/#str) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο προορισμού. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/el/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. |
| [`read_workbook_stream(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/read_workbook_stream/#) | Γράφει το εσωτερικά περιεχόμενο βιβλίο εργασίας Excel σε μια ροή. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/el/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Αρχικοποιεί το εσωτερικά περιεχόμενο βιβλίο εργασίας Excel με τιμή που καθορίζεται από το χρήστη. |
| [`get_range(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/get_range/#) | Λαμβάνει την περιοχή δεδομένων του διαγράμματος. |
| [`set_range(self, formula)`](/slides/python-net/el/aspose.slides.charts/chartdata/set_range/#str) | Ορίζει την περιοχή δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει της νέας περιοχής δεδομένων.<br/>            Εάν ο αριθμός των σειρών στην περιοχή δεδομένων είναι μεγαλύτερος από τον αριθμό των σειρών στα δεδομένα του διαγράμματος, τότε επιπλέον σειρές με τον ίδιο τύπο<br/>            όπως η τελευταία σειρά στην τρέχουσα συλλογή θα προστεθούν στο τέλος της συλλογής. |
| [`refresh_data(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/refresh_data/#) | Ανανεώνει τα δεδομένα του διαγράμματος φορτώνοντάς τα ξανά από το βιβλίο πηγής. |
| [`switch_row_column(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/switch_row_column/#) | Ανταλλάσσει τα δεδομένα κατά τον άξονα.<br/>            Τα δεδομένα που απεικονίζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)