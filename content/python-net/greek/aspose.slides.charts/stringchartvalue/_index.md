---
title: StringChartValue class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/stringchartvalue/
---
## StringChartValue κλάση

Αναπαριστά τιμή συμβολοσειράς που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους:
1) σε κελί/κελιά του φύλλου εργασίας που σχετίζεται με το γράφημα;
2) ως κυριολεκτική τιμή.

**Κληρονομικότητα:**[`StringChartValue`](/slides/python-net/el/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/el/aspose.slides.charts/basechartvalue)

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`data_source_type`](/slides/python-net/el/aspose.slides.charts/stringchartvalue/data_source_type/) | Καθορίζει αν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble <br/>            είναι ενεργή στα παράγωγα. Με άλλα λόγια καθορίζει τον τύπο <br/>            της τιμής της ιδιότητας Data.<br/>            Ανάγνωση/εγγραφή [`DataSourceType`](/slides/python-net/el/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/el/aspose.slides.charts/stringchartvalue/data/) | Επιστρέφει ή ορίζει το αντικείμενο Data.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`as_cells`](/slides/python-net/el/aspose.slides.charts/stringchartvalue/as_cells/) | Η ανάθεση τιμής Null δεν επιτρέπεται.<br/>            Η επιστρεφόμενη τιμή είναι πάντα διαφορετική από None.<br/>            Ανάγνωση/εγγραφή [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/el/aspose.slides.charts/stringchartvalue/as_literal_string/) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά.<br/>            Ανάγνωση/εγγραφή **str**. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/el/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Ορίζει την τιμή από το καθορισμένο κελί. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/el/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Αν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση<br/>            των κελιών στο φύλλο εργασίας που αντιπροσωπεύουν τα δεδομένα συμβολοσειράς. Διαφορετικά επιστρέφει<br/>            κενή συμβολοσειρά. |

### Δείτε επίσης
* κλάση [`BaseChartValue`](/slides/python-net/el/aspose.slides.charts/basechartvalue)
* κλάση [`StringChartValue`](/slides/python-net/el/aspose.slides.charts/stringchartvalue)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)