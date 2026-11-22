---
title: DataLabel class
second_title: Αναφορά API Aspose.Slides for Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.charts/datalabel/
---
## DataLabel κλάση

Αντιπροσωπεύει ετικέτες σειράς.

Ο τύπος DataLabel εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/el/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Δημιουργεί μια νέα παρουσία της κλάσης DataLabel. |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/el/aspose.slides.charts/datalabel/chart/) | Επιστρέφει το γονικό γράφημα.<br/>            Μόνο για ανάγνωση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/el/aspose.slides.charts/datalabel/is_visible/) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) είναι ψευδείς).<br/>            Μόνο για ανάγνωση **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/el/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι None, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων.<br/>            Το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat.<br/>            Μόνο για ανάγνωση [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/el/aspose.slides.charts/datalabel/text_format/) | Επιστρέφει τη μορφή κειμένου.<br/>            Μόνο για ανάγνωση [`IChartTextFormat`](/slides/python-net/el/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/el/aspose.slides.charts/datalabel/x/) | Επιστρέφει ή ορίζει τη συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του γραφήματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides.charts/datalabel/y/) | Επιστρέφει ή ορίζει τη συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του γραφήματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides.charts/datalabel/width/) | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του γραφήματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides.charts/datalabel/height/) | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του γραφήματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`right`](/slides/python-net/el/aspose.slides.charts/datalabel/right/) | Δεξιά.<br/>            Μόνο για ανάγνωση **float**. |
| [`bottom`](/slides/python-net/el/aspose.slides.charts/datalabel/bottom/) | Κάτω.<br/>            Μόνο για ανάγνωση **float**. |
| [`data_label_format`](/slides/python-net/el/aspose.slides.charts/datalabel/data_label_format/) | Επιστρέφει τη μορφή της ετικέτας δεδομένων.<br/>            Μόνο για ανάγνωση [`IDataLabelFormat`](/slides/python-net/el/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/el/aspose.slides.charts/datalabel/value_from_cell/) | Αποκτά ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true. |
| [`label_shape_type`](/slides/python-net/el/aspose.slides.charts/datalabel/label_shape_type/) | Αποκτά ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων.<br/>             Επιστρέφει [`ShapeType.NOT_DEFINED`](/slides/python-net/el/aspose.slides/shapetype/NOT_DEFINED) αν δεν οριστεί σχήμα. |
| [`actual_x`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_x/) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου γραφήματος σε σχέση με την αριστερή άνω γωνία του γραφήματος.<br/>            Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`actual_y`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_y/) | Καθορίζει το πραγματικό ανώτερο σημείο του στοιχείου γραφήματος σε σχέση με την αριστερή άνω γωνία του γραφήματος.<br/>            Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`actual_width`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_width/) | Καθορίζει το πραγματικό πλάτος του στοιχείου γραφήματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`actual_height`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_height/) | Καθορίζει το πραγματικό ύψος του στοιχείου γραφήματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`slide`](/slides/python-net/el/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/datalabel/presentation/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/el/aspose.slides.charts/datalabel/hide/#) | Κάνει την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) στην κατάσταση ψευδής.<br/>            Το IsVisible θα είναι ψευδές μετά από αυτό. |
| [`get_actual_label_text(self)`](/slides/python-net/el/aspose.slides.charts/datalabel/get_actual_label_text/#) | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/el/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text".<br/>            Αν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)